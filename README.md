# Adwaita theme for Qutebrowser

A theme for [Qutebrowser](https://qutebrowser.org) based on the [Adwaita](https://gitlab.gnome.org/GNOME/gtk/tree/master/gtk/theme/Adwaita) theme.

![Screenshot](https://raw.githubusercontent.com/WammKD/Adwaita-Theme-for-Qutebrowser/master/screenshot.png "Screenshot")

## Installation

- Find your ~/.qutebrowser directory.
- `git clone https://github.com/WammKD/Adwaita-Theme-for-Qutebrowser.git adwaita`
- In ~/.qutebrowser/config.py, add the following:

```python
import adwaita.draw

adwaita.draw.render(c)
```

## More Info

For more information, check out the Qutebrowser documentation on [Configuring Qutebrowser](https://qutebrowser.org/doc/help/configuring.html), in particular the section on config.py.

## Other Cool Themes

* [Dracula Theme](https://github.com/evannagle/qutebrowser-dracula-theme/) by @evannagle, which provided a basis for figuring out how to create _this_ theme
* [Nord Theme](https://github.com/Linuus/nord-qutebrowser/) by @Linuus
* Another [Nord Theme](https://github.com/KnownAsDon/QuteBrowser-Nord-Theme) by @KnownAsDon