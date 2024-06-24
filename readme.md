python3 -m venv dash_project

linux

source dash_project/bin/activate

windows

dash_project/Script/activate.bat

nvm ls-remote

nvm install 14.17.0
nvm use 14.17.0


jupyter labextension install jupyterlab-plotly@4.14.3


%config InlineBackend.figure_format = 'retina'
import matplotlib.pyplot as plt
from plotly.tools import mpl_to_plotly
mpl_fig, ax = plt.subplots()
ax.scatter(x=[1, 2, 3], y=[23, 12, 34])
plotly_fig = mpl_to_plotly(mpl_fig)
plotly_fig




