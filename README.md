# Super Simple Mint-Y in Vivaldi CSS

This is just a repo containing the CSS files that I use to match Vivaldi's default window control buttons in Linux (+ some other tweaks), with the ones that Linux Mint uses.

I initially posted about it in Vivaldi Forums but since I recently corrected issues with it, I just decided to put everything into this GitHub's repo and update it.

This CSS is just intended to replace the default window control buttons of Vivaldi in Linux for the ones that Mint-Y uses (that's why it is called "Super Simple"). Although there are other CSS files, they are just tiny tweaks that I added that I think are a good fit, but not necessary for the window control buttons to be replaced.

## How does it look like?

Here's a comparison:

|       |Maximized                   |Not Maximized                   |
|-------|----------------------------|--------------------------------|
|Default|![default-vivaldi-maximized]|![default-vivaldi-not-maximized]|
|Custom |![custom-mint-y-maximized]  |![custom-mint-y-not-maximized]  |

[custom-mint-y-maximized]: https://github.com/octo-catto/super-simple-mint-y-vivaldi-css/blob/main/sample_screenshots/custom-mint-y-maximized.png
[custom-mint-y-not-maximized]: https://github.com/octo-catto/super-simple-mint-y-vivaldi-css/blob/main/sample_screenshots/custom-mint-y-not-maximized.png
[default-vivaldi-maximized]: https://github.com/octo-catto/super-simple-mint-y-vivaldi-css/blob/main/sample_screenshots/default-vivaldi-maximized.png
[default-vivaldi-not-maximized]: https://github.com/octo-catto/super-simple-mint-y-vivaldi-css/blob/main/sample_screenshots/default-vivaldi-not-maximized.png
[custom-mint-y-vertical-tabs]: https://github.com/octo-catto/super-simple-mint-y-vivaldi-css/blob/main/sample_screenshots/custom-mint-y-vertical-tabs.png

It also works when you enable vertical tabs:
![custom-mint-y-vertical-tabs]

## How does it work?

Vivaldi provides a very useful feature that allows you to modify how the browser looks by using CSS. As of now, the window control buttons in Vivaldi use a SVG path. In Linux Mint, the SVGs used in the window control buttons for Mint-Y can be found in: ```/usr/share/icons/Mint-Y/actions/symbolic```. Then the default ones can be changed for the ones that Mint-Y uses. 

The background color of the close button can easily be changed in case you use Mint-Y theme aside from Aqua.

## Which CSS file should I download then?

* ```lm-mint-y-window-control-buttons.css```
* The other CSS files are completely optional.

