---
layout: page
---

# Awesome WM Widgets

This is a project page of the github repo with set of widgets for Awesome Window Manager

## Prerequisite

To have a consistent color palette through all the widgets add following section to your **theme.lua**. This will also allow you to easily change colors of the widgets in one place. Note that text widgets (for example text in spotify-widget) are using color defined in `theme.fg_normal`.

```lua
-- https://github.com/streetturtle/awesome-wm-widget
theme.widget_main_color = "#74aeab"
theme.widget_red = "#e53935"
theme.widget_yelow = "#c0ca33"
theme.widget_green = "#43a047"
theme.widget_black = "#000000"
theme.widget_transparent = "#00000000"
```

I would also recommend to install [Play](https://fonts.google.com/specimen/Play) font as it looks good and explicitly used in some widgets. However you can easily change font in widget's source.