# Termux:Styling

[![Build status](https://api.cirrus-ci.com/github/termux/termux-styling.svg?branch=master)](https://cirrus-ci.com/termux/termux-styling)
[![Join the chat at https://gitter.im/termux/termux](https://badges.gitter.im/termux/termux.svg)](https://gitter.im/termux/termux)

A [Termux](https://termux.com/) add-on app to customize the terminal font and
color theme.

When developing (or packaging), note that this app needs to be signed with the
same key as the main Termux app in order to have the permission to modify the
required font or color files.

## Installation

Termux:Styling application can be obtained from:

- [Google Play](https://play.google.com/store/apps/details?id=com.termux.styling)
- [F-Droid](https://f-droid.org/en/packages/com.termux.styling/)
- [Kali Nethunter Store](https://store.nethunter.com/en/packages/com.termux.styling/)

Additionally we offer development builds for those who want to try out latest
features ready to be included in future versions. Such build can be obtained
directly from [Cirrus CI artifacts](https://api.cirrus-ci.com/v1/artifact/github/termux/termux-styling/debug-build/output/app/build/outputs/apk/debug/app-debug.apk).

Signature keys of all offered builds are different. Before you switch the
installation source, you will have to uninstall the Termux application and
all currently installed plugins.

## License

Released under the [GPLv3 license](http://www.gnu.org/licenses/gpl-3.0.en.html).

## How to use

1. When inside Termux, long press anywhere on the terminal.
2. Select `More...` in the resulting dialog.
3. Select `Style` in the next dialog.
4. Click either `CHOOSE COLOR` or `CHOOSE FONT` depending on what you want to customize.
