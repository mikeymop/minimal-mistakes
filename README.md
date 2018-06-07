# Minimal Mistakes Hugo Port

I am following a folder structure convention for [separating source](http://thecodestead.com/post/how-to-use-npm-as-a-build-tool-with-hugo/) files

## Structure

### Jekyll Portion

The `_sass` dir from jekyll will have to be maintained with node.js toolchaining. This will acompile the sass files to `/static/css/main.css` for when they are needed.

### Hugo Portion
.
`-- minMistakes
    |-- archetypes
    |   `-- default.md
    |-- config.toml
    |-- layouts
    `-- themes
        `-- minMistakes
            |-- LICENSE.md
            |-- archetypes
            |   `-- default.md
            |-- layouts
            |   |-- 404.html
            |   |-- _default
            |   |   |-- list.html
            |   |   `-- single.html
            |   |-- index.html
            |   `-- partials
            |       |-- footer.html
            |       `-- header.html
            |-- static
            |   |-- css
            |   |   `-- main.scss
            |   `-- js
            |       |-- _main.js
            |       |-- banner.js
            |       |-- lunr
            |       |   |-- lunr-en.js
            |       |   |-- lunr-gr.js
            |       |   |-- lunr-store.js
            |       |   |-- lunr.js
            |       |   `-- lunr.min.js
            |       |-- main.min.js
            |       |-- plugins
            |       |   |-- jquery.fitvids.js
            |       |   |-- jquery.greedy-navigation.js
            |       |   |-- jquery.magnific-popup.js
            |       |   `-- jquery.smooth-scroll.min.js
            |       `-- vendor
            |           `-- jquery
            |               `-- jquery-3.3.1.min.js
            |-- static-src
            |   `-- sass
            |       |-- minimal-mistakes
            |       |   |-- _animations.scss
            |       |   |-- _archive.scss
            |       |   |-- _base.scss
            |       |   |-- _buttons.scss
            |       |   |-- _footer.scss
            |       |   |-- _forms.scss
            |       |   |-- _masthead.scss
            |       |   |-- _mixins.scss
            |       |   |-- _navigation.scss
            |       |   |-- _notices.scss
            |       |   |-- _page.scss
            |       |   |-- _print.scss
            |       |   |-- _reset.scss
            |       |   |-- _search.scss
            |       |   |-- _sidebar.scss
            |       |   |-- _syntax.scss
            |       |   |-- _tables.scss
            |       |   |-- _utilities.scss
            |       |   |-- _variables.scss
            |       |   |-- skins
            |       |   |   |-- _air.scss
            |       |   |   |-- _aqua.scss
            |       |   |   |-- _contrast.scss
            |       |   |   |-- _dark.scss
            |       |   |   |-- _default.scss
            |       |   |   |-- _dirt.scss
            |       |   |   |-- _mint.scss
            |       |   |   |-- _neon.scss
            |       |   |   |-- _plum.scss
            |       |   |   `-- _sunrise.scss
            |       |   `-- vendor
            |       |       |-- breakpoint
            |       |       |   |-- _breakpoint.scss
            |       |       |   |-- _context.scss
            |       |       |   |-- _helpers.scss
            |       |       |   |-- _legacy-settings.scss
            |       |       |   |-- _no-query.scss
            |       |       |   |-- _parsers.scss
            |       |       |   |-- _respond-to.scss
            |       |       |   |-- _settings.scss
            |       |       |   `-- parsers
            |       |       |       |-- _double.scss
            |       |       |       |-- _query.scss
            |       |       |       |-- _resolution.scss
            |       |       |       |-- _single.scss
            |       |       |       |-- _triple.scss
            |       |       |       |-- double
            |       |       |       |   |-- _default-pair.scss
            |       |       |       |   |-- _default.scss
            |       |       |       |   `-- _double-string.scss
            |       |       |       |-- resolution
            |       |       |       |   `-- _resolution.scss
            |       |       |       |-- single
            |       |       |       |   `-- _default.scss
            |       |       |       `-- triple
            |       |       |           `-- _default.scss
            |       |       |-- magnific-popup
            |       |       |   |-- _magnific-popup.scss
            |       |       |   `-- _settings.scss
            |       |       `-- susy
            |       |           |-- _su.scss
            |       |           |-- _susy-prefix.scss
            |       |           |-- _susy.scss
            |       |           |-- plugins
            |       |           |   |-- _svg-grid.scss
            |       |           |   `-- svg-grid
            |       |           |       |-- _prefix.scss
            |       |           |       |-- _svg-api.scss
            |       |           |       |-- _svg-grid-math.scss
            |       |           |       |-- _svg-settings.scss
            |       |           |       |-- _svg-unprefix.scss
            |       |           |       `-- _svg-utilities.scss
            |       |           `-- susy
            |       |               |-- _api.scss
            |       |               |-- _normalize.scss
            |       |               |-- _parse.scss
            |       |               |-- _settings.scss
            |       |               |-- _su-math.scss
            |       |               |-- _su-validate.scss
            |       |               |-- _syntax-helpers.scss
            |       |               |-- _unprefix.scss
            |       |               `-- _utilities.scss
            |       `-- minimal-mistakes.scss
            `-- theme.toml
```
