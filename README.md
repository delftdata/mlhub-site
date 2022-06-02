# Modelsearch Site

## Updating the site

In order to update the site, build the Quasar project at https://github.com/delftdata/modelsearch-project, and then copy the contents of the resulting `/dist/spa/` folder into this repository's folder after pulling it, overwriting the old files, and then commit/push.

If you get a NodeJS memory error while building, try setting the following Node environment variable before building in the same terminal: `NODE_OPTIONS=--max_old_space_size=4096`
