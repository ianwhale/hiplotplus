# HiPlotPlus

Interactive, high dimensional plotting with parallel coordinates plots. A fork of Facebook Research's archived `hiplot` library.

This new package retains the original `hiplot` functionality:
- Simple Python interface for `pandas` DataFrames.
- Offline viewable, interactive HTML exports.

## Development plan

Overall plan is to retain the Python API and major functionality, this should be a drop in replacement for `hiplot`.

Currently the development goals are:
- Update the project to use `uv` and either `hatch` or `uv`'s build system.
- Update circleci to github actions.
- Remove as much javascript as possible, try to use D3 assets to remove the need for custom code (maybe?).
- Performance, package size, compression, etc.
- Make the interface more beautiful!
- Expand to other DataFrame inputs (maybe?).

## Alternatives

There are plenty of alternatives to this work.

- The original, archived Facebook Research package: [https://github.com/facebookresearch/hiplot](https://github.com/facebookresearch/hiplot)
- Plotly: [https://plotly.com/python/parallel-coordinates-plot/](https://plotly.com/python/parallel-coordinates-plot/) 
- Pandas: [https://pandas.pydata.org/docs/reference/api/pandas.plotting.parallel_coordinates.html](https://pandas.pydata.org/docs/reference/api/pandas.plotting.parallel_coordinates.html)
- D3: [https://d3-graph-gallery.com/parallel.html](https://d3-graph-gallery.com/parallel.html)
- YellowBrick: [https://www.scikit-yb.org/en/latest/api/features/pcoords.html](https://www.scikit-yb.org/en/latest/api/features/pcoords.html)

However, `hiplotplus` retains and updates the original, unique functionality of `hiplot`. Where high quality, interactive plots can be shared amongst practitioners.
