# Plotly Tutorials

Documentation link: https://plotly.com/python/

GitHub - https://github.com/plotly

## Fundamentals
### Plotly express [file](Plotly1_Fundamentals/plotly1_express.ipynb)
Documentation link: https://plotly.com/python/plotly-express/

To import:
```python
import plotly.express as px
import pandas as pd
```

Here the datasets used are from the module `pd.data`.

+ [scatter plots](https://plotly.com/python/line-and-scatter/) and [discrete color](https://plotly.com/python/discrete-color/) (`.scatter`)
+ [trendlines](https://plotly.com/python/linear-fits/) and [templates](https://plotly.com/python/templates/) and [marginal distribution plots](https://plotly.com/python/marginal-plots/)
+ [eror bars](https://plotly.com/python/error-bars/)
+ [bar charts](https://plotly.com/python/bar-charts/) (`.bar`)
+ [facet plots](https://plotly.com/python/facet-plots/)
+ [scatterplot matrices](https://plotly.com/python/splom/) (`.scatter_matrix`)
+ [parallel coordinates](https://plotly.com/python/parallel-coordinates-plot/) and [parallel categories](https://plotly.com/python/parallel-categories-diagram/) and [continuous color](https://plotly.com/python/colorscales/) (`.parallel_coordinates` and `.parallel_categories`)
+ [hover labels](https://plotly.com/python/hover-text-and-formatting/)
+ [animations](https://plotly.com/python/animations/)
+ [line charts](https://plotly.com/python/line-charts/) (`.line`)
+ [area charts](https://plotly.com/python/filled-area-plots/) (`.area`)
+ [timeline/ Gantt charts](https://plotly.com/python/gantt/) (`.timeline`)
+ [funnel charts](https://plotly.com/python/funnel-charts/) (`.funnel`)

Part to Whole Charts -
+ [pie charts](https://plotly.com/python/pie-charts/) (`.pie`)
+ [sunburst charts](https://plotly.com/python/sunburst-charts/) (`.sunburst`)
+ [treemaps](https://plotly.com/python/treemaps/) (`.treemap`)
+ [icicle charts](https://plotly.com/python/icicle-charts/) (`.icicle`)

Distributions -
+ [histograms](https://plotly.com/python/histograms/) (`.histogram`)
+ [box plots](https://plotly.com/python/box-plots/) (`.box`)
+ [violin plots](https://plotly.com/python/violin/) (`.violin`)
+ [Empirical cumulative distribution function (ECDF) charts](https://plotly.com/python/ecdf-plots/) (`.ecdf`)
+ [strip charts](https://plotly.com/python/strip-charts/) (`.strip`)
+ [density contours or 2d histogram contours](https://plotly.com/python/2d-histogram-contour/) (`.density_contour`)
+ [density heatmaps or 2d histograms](https://plotly.com/python/2D-Histogram/) (`.density_heatmap`)

[Images and Heatmaps](https://plotly.com/python/imshow/) (`.imshow`, `from skimage import io`)

Polar Coordinates -
+ [polar plots](https://plotly.com/python/polar-chart/) (`.scatter_polar`)
+ [radar charts](https://plotly.com/python/radar-chart/) (`.line_polar`)
+ [polar bar charts](https://plotly.com/python/wind-rose-charts/) (`.bar_polar`)

3D Coordinates -
+ [3D scatter plots](https://plotly.com/python/3d-scatter-plots/) (`.scatter_3d`)

[Ternary Coordinates](https://plotly.com/python/ternary-plots/) (`scatter_ternary`)

Bash

### Plotly graph objects [file](Plotly1_Fundamentals/plotly1_graph_objects.ipynb)
Documentation Link: https://plotly.com/python/graph-objects/

To import:
```python
import plotly.graph_objects as go
```
* Comparing Graph Objects and Plotly Express

An example of code is given below -
```python
fig = go.Figure()
fig.add_trace(go.Bar(x=, y=, name=, hovertemplate=))
fig.update_layout(legend_title_text = "")
fig.update_xaxes(title_text = "")
fig.update_yaxes(title_text = "")
fig.show()
```
See this code in the file.

## Basic Charts

## Statistical Charts

## Scientific Charts

## Subplots

## 3D Charts

## Jupyter widget interaction

## Transforms

## AI and ML

## Animations

## Add Custom Controls
