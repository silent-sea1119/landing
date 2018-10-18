# Single scrolled landing page - WP Theme

![alt text](https://github.com/parys-github/landing/blob/master/screenshot.png "Screenshot")

>You can find here a scrolled **WordPress** theme as a single landing page.
This is a popular single page but in this case, you have a custom template that loads independently all pages from the WordPress dashboard as one scrolled content. Full keyboard control.

The template does not use any fancy plugins or heavy libraries. Just **Advanced Custom Fields** and then all pages as sections load only once. Additionally, a maximum optimized code with **Gulp** makes the whole web page load very fast.

Implemented libraries:
* jQuery
* Swiper Slider
* iziModal
* Scrollify
* AnimateCSS

## Build Setup

``` bash
# Download or clone theme package
git clone https://github.com/parys-github/landing.git

# Install NPM package, and any packages that it depends on.
npm install

# run build for production with minification => /build/ directory
gulp

```

## Features
* All Wordpress pages as one scrolled content
* Custom navigation build via ACF
* Optimised and minified files via GULP
* SCSS source files (compiled CSS included)
* Javascript sources are written using ES6 (compiled JS included)
* Extra WPML integration with (Arabic) RTL styles orientation
* Swiper Slider integrated with WP Pages
* Animations with AnimateCSS
* Customisable modals
* Mobile view compatible

## Project Structure
```
..git/                             # git repo
│   └── ...
├── wp-admin/                      # wordpress structure
│   └── ...
├── wp-content/                    # Wordpress structure
│   └── themes/                    # WP themes directory
│   │   └──landing/                # Landing themes directory (landing)
│   │        ├── build/            # Final build JS and Style minified files
│   │        │   └── css/          # Theme styles
│   │        │   └── img/          # Theme artwork assets
│   │        │   └── js/           # Theme scripts
│   │        ├── parts/            # Template parts
│   │        │   └── ...           # Individual pages templates
│   │        └── src               # Template source directory
│   │            ├── sass/         # Stylesheet SCSS files and vendors styles
│   │            └── scripts/      # Main app.js and vendors libraries
│   │        ├── footer.php        # Footer template
│   │        ├── functions.php     # Basic theme functions file
│   │        ├── gulp.js           # Gulp configuration file
│   │        ├── header.php        # Header template
│   │        ├── index.php         # Theme index
│   │        ├── package.json      # Basic Node packeges config
│   │        ├── package-lock.json # Package-lock.json
│   │        ├── README.md         # Instruction file
│   │        ├── screenshot.png    # Theme screenshot thumbnail
│   │        └── style.css         # Default WP theme style info
├── wp-includes/                   # Wordpress structure
```

## Additional documentation

[Advanced Custom Firlds](https://www.advancedcustomfields.com/)

[Gulp.js](https://gulpjs.com/)

[jQuery](https://jquery.com/)

[Swiper Slider](http://idangero.us/swiper/)

[animate.css](https://daneden.github.io/animate.css/)

[iziModal](http://izimodal.marcelodolce.com/)

[Scrollify](https://projects.lukehaas.me/scrollify/#home)

[Pictures sample taken from free platform UNSPLASH.COM](https://unsplash.com/)


### Demo

[www.landing.vajracode.net](https://www.landing.vajracode.net/)

Example pages and ACF json conf file available to download at demo website


