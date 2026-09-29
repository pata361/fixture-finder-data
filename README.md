# fixture-finder-data

Published fixture library data for the [Fixture Finder](https://github.com/pata361/fixture-finder) app.

This repo exists only so the app can fetch a newer fixture library over the air
(Meine → Fixture-Bibliothek → Auf Updates prüfen). It contains no app code.

## Contents

- `dataset-manifest.json` - current version, fixture count, and the URL of the dataset file.
- `ofl-runtime.json` - the compact fixture dataset itself, generated from the
  [Open Fixture Library](https://open-fixture-library.org/) (MIT licensed) via
  `scripts/import-ofl.mjs` and `scripts/publish-dataset.mjs` in the main repo.

## License / attribution

Fixture data derives from the Open Fixture Library
(https://github.com/OpenLightingProject/open-fixture-library), MIT licensed.
See `dataset-manifest.json` for attribution details.
