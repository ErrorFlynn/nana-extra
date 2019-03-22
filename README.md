# nana-extra <a href="https://www.buymeacoffee.com/besh81" target="_blank"><img align="right" src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
A collection of [Nana C++ Library](https://github.com/cnjinhao/nana) custom controls developed by users

#### Refer to [WIKI](https://github.com/besh81/nana-extra/wiki) for documentation and examples


## [propertygrid](https://github.com/besh81/nana-extra/wiki/propertygrid)
**Author: besh81**

A specialized grid for editing properties. It comes with a list of ready-to-use property classes include strings, numbers, flag sets, colors and many others.

<img src="https://github.com/besh81/nana-extra/blob/master/screenshots/propertygrid.png" alt="propertygrid" height="450"></a>

## [plot2d](https://github.com/besh81/nana-extra/wiki/plot2d)
**Author: [JamesBremner](https://github.com/JamesBremner)**

A 2D plotting widget for the nana library.

The plot contains one or more traces.

Each trace can be of one of three types:

- Plot: succesive y-values with line drawn between them.
- Scatter: succesive x,y-values with box around each point
- Realtime: a specified number of the most recent y-values

Any number of plot and scatter traces can be shown together,
only one realtime trace may be present in a plot.

### Files:

plot2d/plot.h, plot2d/plot.cpp - widget code, add to your projects

plot2d/demos/main.cpp - demo application code

plot2d/demos/nanaplot.cbp - codeblocks project to build demo application

plot2d/demos/realtime/* - realtime plotting demo application

plot2d/demos/spline/* - spline curve demo application

<img src="https://github.com/besh81/nana-extra/blob/master/screenshots/SplineCurve.PNG" alt="plot2d"></a>

## panel_scrolled
**Author: [JamesBremner](https://github.com/JamesBremner)**

Nana panel specialization to display small visible scrollable part of the panel

The scrolled panel is large and mostly hidden.  The widgets are placed on this panel.

The visible panel is small and transparent, allows user to see a small part of the scrolled panel.

The visible panel is surrounded by scroll bars which control what part of scrolled panel is seen.

The visible panel and scroll bars are constructed automatically, to the dimensions specifed in the scrolled panel constructor
    
### Files:

panel_scrolled/panel_scrolled.h  Needs header only, include in source file where referenced

panel_scrolled/demos/* - demo application code
    
<img src="https://github.com/besh81/nana-extra/blob/master/screenshots/panel_scrolled.png" alt="panel_scrolled"></a>

## progress_ex
**Author: [ErrorFlynn](https://github.com/ErrorFlynn)**

`progress_ex` is a simple extension of the `nana::progress` class, adding text to the widget and a few color presets. It modifies none of the existing behavior of the base class, and is constructed and used in exactly the same way. For details, please see the **[documentation](https://besh81.github.io/nana-extra/progress_ex/progress_ex.html)**.

![progress_ex demo screenshot](https://raw.githubusercontent.com/besh81/nana-extra/master/screenshots/progress_ex.png)
