# lxqt-themes-oxygen

This repository contains an LXQt port of the Oxygen style, first appearing in KDE Plasma 4 and still around in 5.x (and presumably 6.x, when that comes out). A color scheme is included to go along with the
theme file. It is recommended to have the Oxygen Qt engine installed and selected, or applications and scrollbars will not render correctly.

Because LXQt handles SVG images differently than KDE Plasma -- in particular, there is no "hint-stretch-borders" directive -- many of the SVG assets in this file are modified from the
base widgets of the Plasma theme. Additionally, some (like the glows on taskbar items) aren't image files at all, but rather close approximations using the Q[Linear/Radial]Gradient QSS
primitives! As a result, this theme is not pixel-perfect, but it's close enough that you would need to examine screenshots in an image editor to spot the differences.

The base LXQt desktop with the theme applied -- using a Lubuntu port of the old Box theme and the Oxygen icon set:
![LXQt-Oxygen](https://github.com/AzumaHazuki/lxqt-themes-oxygen/assets/67122280/48cb8c49-0e5d-4649-97f4-e7fcd142ba31)

Popup menus (QMenu class) styled with grey gradient look:
![LXQt-Oxygen-Menu](https://github.com/AzumaHazuki/lxqt-themes-oxygen/assets/67122280/47473458-c2cb-4e01-b57a-a762c222efca)

The LXQt Runner mimics KRunner somewhat:
![LXQt-Oxygen-Runner](https://github.com/AzumaHazuki/lxqt-themes-oxygen/assets/67122280/0f9cfccf-da26-4abd-bb80-39e2b0d3a9ad)

The theme even includes support for the as-yet-unreleased Wing Menu plugin!
![LXQt-Oxygen-WingMenu](https://github.com/AzumaHazuki/lxqt-themes-oxygen/assets/67122280/a973a132-9ce1-4818-8f10-987fbc9ce0f5)
