
## What it does?
* Quickly share part of your screen, other apps thinking that it's a whole screen
* Large screens - share only small part
* Large screens - when sharing small part fonts are big enough
* Sets a separate wallpaper for shared part - easy to distinguish shared part

![Example][example.gif]

## Usage
* Put file into PATH
* Adjust paths to wallpapers (BASE_WALLPAPER, SHARE_WALLPAPER)
* Adjust virtual screen size and position next to the xrandr command
* Turn on share area by calling `share-area-with-wallpaper on`
* Turn off share area by calling `share-area-with-wallpaper off`


## Dependencies
* xrandr
* nitrogen

## Links
* [Linux Virtual Monitors with xrandr](https://chipsenkbeil.com/notes/linux-virtual-monitors-with-xrandr/)
* [xrandr format explanation/xrandr virtual splitscreen cookbook](https://mrwaggel.be/post/xrandr-virtual-splitscreen-cookbook/)
