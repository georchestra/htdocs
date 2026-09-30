# Header configuration

For master branch, the geOrchestra configuration usually points to the CDN address, and the header ships with its default style and config.

The following files should only be provided for releases of geOrchestra (i.e. docker compose versions) in order to freeze the header config into something that works for the current version of the compo. This ensures that the menu is in sync with the provided apps and paths, that can and will vary over time.

- header.js: snapshot from the CDN at the time of a geOrchestra release
- header-config.json: originally taken from https://github.com/georchestra/header/blob/main/src/default-config.json. Minimally adapted to match the currently served paths.
- header-styles.css: originally taken from https://github.com/georchestra/header/blob/main/public/georchestra.css. 

