<a href="https://picturepan2.github.io/spectre">
  <img src="https://picturepan2.github.io/spectre/img/spectre-logo.svg" width="72" height="72">
</a>

## Spectre.css

Spectre.css is a lightweight, responsive and modern CSS framework.

- Lightweight (~10KB gzipped) starting point for your projects
- Flexbox-based, responsive and mobile-friendly layout
- Elegantly designed and developed elements and components

Spectre is a side project based on years of CSS development work on a large web service project. Spectre only includes modern base styles, responsive layout system, CSS components and utilities, and it can be modified for your project with Sass/Scss compiler.

Spectre.css is completely free to use. If you enjoy it, please consider [donating via Paypal](https://www.paypal.me/picturepan2) for the further development. ♥ 

## Getting started

### Compiling custom CSS from SASS in `/src` folder

Spectre uses Gulp for compiling CSS. Firstly you need to install NPM, which is used to manage Gulp and other dependencies.

Then, you can build the CSS file from the command-line:

1. Navigate to the root director of Spectre
2. Run `npm install`. NPM will install all dev dependencies as listed in package.json
3. When completed, run `gulp build` to compile Sass to CSS and minify files
4. You can find compiled CSS files in the /dist directory

### All available Gulp tasks:

- `gulp build` - compile Sass to CSS and minify files (default)
- `gulp docs` - compile documentation
- `gulp watch` - watch file changes and re-compile CSS files

## Archer templete SASS: `/src/_archer.scss`

Archer-specific customizations of the base Spectre styles are included in `/src/_archer.scss` and get compiled into the final CSS whenever `gulp build` or `gulp watch` is run.



## Browser support

Spectre uses [Autoprefixer](https://github.com/postcss/autoprefixer) to make most styles compatible with earlier browsers and [Normalize.css](https://necolas.github.io/normalize.css/) for CSS resets. Spectre is designed for modern browsers. For best compatibility, these browsers are recommended:

- Chrome (LAST 4)
- Microsoft Edge (LAST 4)
- Firefox (EXTENDED SUPPORT RELEASE)
- Safari (LAST 4)
- Opera (LAST 4)
- Internet Explorer 10+

Spectre supports Internet Explorer 10+, but some HTML5 and CSS3 features are not perfectly supported by Internet Explorer.

Designed and built with ♥ by [Yan Zhu](https://twitter.com/picturepan2). Feel free to submit a pull request. Help is always appreciated.
