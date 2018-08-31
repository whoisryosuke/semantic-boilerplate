# Semantic Boilerplate

Multi-purpose HTML5 templates using [Semantic UI](https://semantic-ui.com/).

## Templates

* Index
* Index Alternative
* Dashboard
* Login

## Getting Started

To start up the development server:

* `git clone `
* cd `project-folder`
* `npm install`
* `npm start`

The dev server is powered by Browsersync and Gulp, which provides hot-reloading when you save files.

## Development

### Semantic UI

This project uses the Semantic UI design system (CSS and JS framework) to primarily style the site. Check out the official SUI docs for more info on how to use elements like the Grid, or Buttons.

This project is configured to use the default SUI theme. If you'd like to customize any part of it, or change the theme, you can make edits in `/semantic/` and then run `gulp build` inside that folder to re-build the CSS to `/dist/`.

### SASS

This project is also setup to use SASS if you'd like. Add any SASS to `assets/sass` then run `npm run gulp` to build any SASS to CSS.

## Credits

* [Semantic UI](https://semantic-ui.com/)
* [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)
* [SASS Boilerplate by @olefredrik](https://github.com/olefredrik/sass-boilerplate)