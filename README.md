# mixer

A fork of [StayPuft](https://github.com/dlecina/StayPuft) which is a fork of the default theme for [Ghost](https://github.com/tryghost/ghost/).

## Features

* Responsive design.
* Post comments using [Disqus](http://disqus.com/).
* In-site search using [GhostHunter](https://github.com/i11ume/ghostHunter).
* Support for [Font Awesome](https://github.com/FortAwesome/Font-Awesome).
* Basic support for [slidr.js](https://github.com/bchanx/slidr).
* Syntax highlighting using [Prism](https://github.com/LeaVerou/prism/).

## Demo

This theme is being used in my [blog](http://bmitch.co/).

## Installation

* Clone this repository on your themes folder:

```
cd ghost/content/themes
sudo git clone https://github.com/bmitch/mixer
```

* **[Configure](#configuration) the theme.**
* Restart Ghost.
* Select the theme in your Settings page.

## Configuration

* Replace `assets/favicon.png` with your own favicon, or remove for the default Ghost favicon.
* Modify `partials/disqus.hbs` with your shortname.
* Replace `partials/copyright.hbs` with your own disclaimer.
* Modify `partials/sidebar-external.hbs` with your own external links.
* After configuration, you may have to restart for all changes to take place. ```service ghost restart```

