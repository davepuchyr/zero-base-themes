# dmjp:

1. Customize themes/zero-black-matrix.less.
2. Run grunt in less/.
3. Add customization to chrome using [this](http://superuser.com/a/247654).

# Notice
Experiments settings reset in `44.0.2403.89`. Open developer tools settings &#9654; Experiments &#9654; [&#10004;] Allow custom UI themes to enable theme again.

# Chrome Default Dark Theme

Chrome now has a default dark theme, that you can enable via Settings > Appearance > Theme: Dark. It's a great step in the right direction, well done Chrome Team! For those if you who want more customization, Zero Base Themes is here for you :)

# Zero Base Themes

An assortment of Chrome Devtools theme that use the Zero Base Template.


# Contributing

Zero Base Themes is built on LESS. Grunt is used to listen for changes to LESS files and generates CSS. This means [Node](http://nodejs.org/) is required.


## Getting Started

1. Clone this repo: `git clone https://github.com/mauricecruz/zero-base-themes.git`.

2. Install dependencies: `npm install`.

3. To use an existing theme: `grunt`. (If you're going to work on your own theme: `grunt watch` to listen for changes).

4. `Chrome > Preferences... > Extensions > DevTools Theme: Zero Dark Matrix = Enabled` (also enable `Allow incognito` below if you wish).

5. chrome://flags (make sure `Enable Developer Tools experiments` is enabled).

6. In Chome Dev Tools > Settings (cog icon or `Shift+?`) > Experiments > Allow custom UI themes.

7. Sometimes it's required to close and reopen the dev tools.


## Contributing to Template Source

All template files are located in the `/less` directory. Files beginning with an `_` indicate template partials. They are imported via `build.less`. Any addition/removal of template partials should be reflected in the build file.


## Changing Themes

Copy `/themes/_theme-template.less` and modify color values accordingly. Rename the file and save in the `/themes` directory. Specify the theme of your choice in `config.less`.

