# How to make your custom build of Analytics.js

1. Fetch the latest version
1. Run `npm install`
1. Run `make clean` to have a clean state
1. Run `make components`
1. Select the integrations you need in `components/segmentio-analytics.js-integrations/lib/slugs.json`
1. Remove the unnecessary files in `components/segmentio-analytics.js-integrations/component.json`
1. Run `make analytics.js`
1. Voila!
