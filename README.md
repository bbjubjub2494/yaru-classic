# Yaru gtk-, gnome-shell-, icon- and sound-theme for Ubuntu using the GNOME desktop

Snap build status: [![Build Status](https://travis-ci.org/ubuntu/yaru.svg?branch=master)](https://travis-ci.org/ubuntu/yaru)

The Yaru theme is the default theme for Ubuntu, backed by the community.
This is the theme that is shaped by the community on the Ubuntu hub, turned into the default theme starting from Ubuntu 18.10 Cosmic Cuttlefish.

More information is available at https://community.ubuntu.com/t/faq-ubuntu-new-theme/1930.

Detailed screenshots and reasoning behind the design can be found inside the Design Wiki: https://github.com/ubuntu/yaru/wiki

![Files](https://i.imgur.com/ZNsVGmK.png)

![Dash](https://i.imgur.com/dT2JtVl.png)

![Appgrid](https://i.imgur.com/N0cmNXQ.png)

![Popups](https://i.imgur.com/mNu0mYF.png)

![Files_and_Shotwell](https://i.imgur.com/fpz7IYG.png)

![System_shutdown](https://i.imgur.com/vMeQiCX.png)

![widgetfactorylight](https://i.imgur.com/Iau8WZo.png)

It contains:
 * a GNOME Shell theme
 * a GTK2 and GTK3 theme
 * an icon & cursor theme, derived from the Unity8 Suru icons and [Suru icon](https://snwh.org/suru) theme.
 * a sound theme, combining sounds from the [WoodenBeaver](https://github.com/madsrh/WoodenBeaver) and [Touch-Remix](https://github.com/madsrh/TouchRemix) sound themes with an emphasis on making sound a usability feature instead of an annoyance.

## Yaru on Ubuntu 18.10

Yaru theme will be the default in 18.10. Once you install it, you will get it by default as part of the distribution soon and will be automatically migrated to it.

You will receive there at regular intervals stable updates of the theme.

## Install Yaru/Communitheme snap on Ubuntu 18.04 (bionic beaver)

> Note that for backward compatibility, we kept the name "communitheme" for bionic beaver. It's up to date with bionic branch of Yaru where we try to cherry-pick as much Gtk and Icon theme changes from master as possible. However the shell theme is more or less set in stone now, since we can not theme both 3.28 and 3.30+ shell in one theme and at some point we will maybe stop to update the bionic branch completely

*Note that these steps only work on Ubuntu 18.04 (bionic beaver).*

Follow these steps in order to install and enable communitheme.

1. Install the communitheme snap on 18.04 by installing `communitheme` in the Ubuntu Software Application or running `snap install communitheme`.
2. Restart your computer. The login screen will now use Communitheme by default. Click on your user, click on the gear icon ans select the "Ubuntu with communitheme snap" session from the login screen, and login.
3. Now everything is using the communitheme including applications, icons, sound notifications and cursor. Any new update of communitheme will come directly to you on a regular basis thanks to the snap without having to run any command!

![install](https://i.imgur.com/Vykmt6N.gif)

![login](https://i.imgur.com/1boZU4F.gif)


### Tracking latest bionic branch changes

By default, you track manually tested and curated releases of communitheme snap. You can use the latest bionic branch changes, as a snap is built
and published to the snap store when any project related to the bionic yaru branch has changed (being GNOME Shell theme, or icon or…).

For switching to it, you can switch to the **edge** channel, by running: `snap refresh communitheme --edge`.
If you want to follow the **edge** content for snap applications, you will need as well to switch `gtk-common-theme` snap
to the same channel: `snap refresh gtk-common-themes --edge`.

If you haven't install the snap yet but want to directly track the edge channel, you can run `snap install communitheme --edge`.

## Copying or Reusing

This project has mixed licencing. You are free to copy, redistribute and/or modify aspects of this work under the terms of each licence accordingly (unless otherwise specified).

The Suru icon assets (any and all source `.svg` files or rendered `.png` files) are licensed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/).

Included scripts are free software licensed under the terms of the [GNU General Public License, version 3](https://www.gnu.org/licenses/gpl-3.0.txt).

## I want to be part of it!

Great, we're looking forward to your PR!

Read [CONTRIBUTING.md](./CONTRIBUTING.md) to figure out how to get started.
