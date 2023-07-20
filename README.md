<img src="https://synappser.github.io/images/apps/trasheye.png" alt="Logo" width="128" />


# TrashEye

**Simply a Trash Can on your Desktop**

With my laptop’s small display, I have Dock-hiding always turned on – anyway the trash icon doesn’t show the file count and a quick Command-Option-D brings it back. Like many of you, I got used to the Trash Can on the Desktop with DragThing that I later replaced with Bin-it until the latter was also discontinued.

[Read more...](https://synappser.github.io/apps/trasheye/)

This repository is a placeholder for its public beta issues and feature requests.

## Companion Widget

**New!** TrashEye now has a BetterTouchTool Touch Bar companion trash can widget that, beyond showing the number of trashed items, allows you to open the local trash bin by touching the widget’s icon.

<img src="https://synappser.github.io/images/apps/companion-widget-cropped.gif" alt="Companion Widget" width="518" />

**[Download the widget](https://github.com/synappser/Companion/releases/download/v1.0/Companion_v1.0.zip?raw=true)** (installation instructions in the zip file)

## FAQ

#### Is this a pre-release?

Yes, TrashEye is currently in public beta.

#### Is it free to download?

Yes, TrashEye is free while it's in beta.

## Features

- Sliding the switch to On in the Preferences window, displays a Trash icon in the bottom left corner of your Desktop
- A single click (left-click) on TrashEye's icon opens the Bin folder
- Right-clicking on the Trash Can opens a contextual menu
- To reposition the Trash on your Desktop click the Reposition Trash menu item. This action will reveal its background view, allowing you to grab it and move it to your liking
- "Force Empty Trash" deletes locked files. It auto-detects if Touch ID is enabled for sudo and adapts its strategy accordingly (see below for a Howto):
  - [How to enable Touch ID for sudo on MacBook Pro](https://azimi.io/how-to-enable-touch-id-for-sudo-on-macbook-pro-46272ac3e2df)
  - [Can Touch ID for the Mac Touch Bar authenticate sudo users and admin privileges?](https://apple.stackexchange.com/questions/259093/can-touch-id-for-the-mac-touch-bar-authenticate-sudo-users-and-admin-privileges)
- Dragging items on to TrashEye's Desktop icon adds them to the trash
- Dragging installer volumes to TrashEye's Desktop icon ejects them

## Roadmap

- [x] Make it possible to resize trash icon
- [x] Trash image should adapt to dark mode like the regular one in the dock
- [x] Add slight transparency on red badge (see system preferences badge in Dock)
- [x] The badge is clipping on its parent view when going from 1/0 or 0/1
- [x] Offer a BetterTouchTool Touch Bar companion Trash Can widget
- [ ] Count hidden trashed files option
- [ ] Add a separate general Keyboard Shortcut to open Preferences window
- [ ] Open Trash and Empty Trash as menu bar items
- [ ] Add an option to double-click to open Trash instead of a single click
- [ ] Add a reset option to move the trash back to its default position
- [ ] Add a general Restore Default Settings option
- [ ] 10000 will also clip (set to 10k+ when above 9999)
- [ ] Change menu bar icon according to empty/full trash can
- [ ] Add multiple icons to choose from
- [ ] Add option to disable count red badge
- [ ] Add global shortcut to show trash content before emptying

## System Requirements

Mac computer with an Apple silicon or Intel processor (macOS 11.0 or newer)

## Settings

<img src="https://synappser.github.io/images/betas/zoom-te.png" width="526" />

## Support

To submit issues or feature requests, please head to the [Issues](https://github.com/synappser/TrashEye/issues) page. You might first need to (freely) sign up to a GitHub account if you do not already have one.
