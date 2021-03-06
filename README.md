Material Values
===============

All the values from the [Material Design guidelines](https://material.google.com) defined in resources for Android.


Available values
----------------

Style
- [Color](https://aodevblue.github.io/MaterialValues/style/colors/) 
- [Icon](https://aodevblue.github.io/MaterialValues/style/icons/)
- [Typography](https://aodevblue.github.io/MaterialValues/style/typography/)

Layout
- [Metrics & keylines](https://aodevblue.github.io/MaterialValues/layout/keylines/)
- [Responsive UI](https://aodevblue.github.io/MaterialValues/layout/responsive_ui/)
- [Elevation](https://aodevblue.github.io/MaterialValues/layout/elevation/)

Components
- [Bottom navigation](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/bottom_navigation.xml)
- [Bottom sheets](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/bottom_sheet.xml)
- [Buttons](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/button.xml)
- [Cards](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/card.xml)
- [Chips](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/dialog.xml)
- [Dialogs](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/dialog.xml)
- [Dividers](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/divider.xml)
- [Expansion panels](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/expansion_panel.xml)
- [Grid lists](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/grid_list.xml)
- [Lists](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/list.xml)
- [Menus](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/menu.xml)
- [Steppers](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/stepper.xml)
- [Subheaders](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/subheader.xml)
- [Tooltips](https://github.com/AoDevBlue/MaterialValues/blob/master/material-values/src/main/res-component/values/tooltip.xml)


If a section of the Material Design specs is not in the above list, it may be because it has no values or is only available on desktop.

Note that the values for the following components are not available as they are already well implemented in Android: Selection controls, Sliders, Snackbars & toasts, Tabs, Text fields.


Usage
-----

Just add this dependency to your build.gradle:
```
compile 'blue.aodev:material-values:1.0.1'
```

The artifact is currently only available on jCenter, not mavenCentral.
Make sure that your buildscript repositories include jCenter.

Use the [documentation](https://aodevblue.github.io/MaterialValues/) for information about values and their usage.


Remaining tasks
---------------

- Finish the documentation
- Add missing values in Layout (Structure)
- Add missing values in Patterns (Navigation drawer, Scrolling techniques)


-----

Inspired by DmitryMalkovich's [material-design-dimens](https://github.com/DmitryMalkovich/material-design-dimens).

© 2016 Ao (Matthieu Esnault) - Released under [Apache-2.0 License](https://raw.githubusercontent.com/AoDevBlue/MaterialValues/master/LICENSE)

