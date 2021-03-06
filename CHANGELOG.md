# Changelog

## 0.5.3

- Upgrade to ember-cli 2.11
- Fix deprecated warning ember-getowner-polyfill
- Switch to ESLint and fixing style

## 0.5.2

- Made the high-charts component “engine friendly” for engine based Ember apps
- Prefer overriding didInsertElement and willDestroyElement

## 0.5.1

- Update to ember-cli 2.7.0
- Don't add fake series when highcharts 'no-data-to-display' module is imported
- Yield chart instance when used in block form

## 0.5.0

- Improve logic for series updates

## 0.4.4

- Add test for 'noData' use case and remove unused code
- Add highmaps demo
- Cleanup documentation
- Add chart drilldown demo
- Add solid gauge demo
- Add sales funnel demo
- Add heat map demo
- Add waterfall demo
- Standardize components in dummp app
- Update to ember-cli 2.5.1
- Fix import boost module before hightchart-3d
- Add scatter chart demo

## 0.4.3

- Clean up tests
- Upgrade to ember-cli 2.4.2
- Add ember observer and code climate badges
- Changed merge -> assign to silent deprecation warning in Ember 2.5
- Update highstock component to be interactive
- Refactor logic for handling chart updates

## 0.4.2

- Redesign dummy app
- Add support for updating chart when series data is removed
- Add integration tests for manipulating series data

## 0.4.1

- Fix path issue for highcharts-more & highcharts-3d

## 0.4.0

- Moving bower dependencies to npm
- Upgrade to ember-cli 1.13.15
- Updating option detection to work with a composed addon
- Use "getOwner" helper to lookup highcharts config

## 0.3.0

- Import Highcharts source from bower

## 0.2.1

- Add support for Ember 2.x
- Fix incorrect import path in chart blueprint

## 0.2.0

- Check that chart exists before calling destroy
- Update Ember CLI to 1.13.8
- Import Highcharts source from NPM instead of vendor files
- Add support for Highcharts 3D
- Add support for Highcharts modules
- [BREAKING] Remove observer in favor of didReceiveAttrs

## 0.1.3

- [DOC] How to override chart redrawing
- Added Highcharts-more

## 0.1.2

- Added chart blueprint
- Added contributing guidelines
- Added Highchart initializer to accept secondary argument

## 0.1.1

- Fix ENOENT error on bower_components
- Include Highcharts source to addon

## 0.1.0

- Update Ember CLI to 0.2.0
- es6ified component
- Remove default chart styles
- Add option to import chart theme
- Make installation process more simple
- Update project description

## 0.0.8

- Fixed broken npm package.

## 0.0.7

- Updated Ember CLI to `0.1.15`.

## 0.0.6

- Updated tests.
- Added Highstock demo to the dummy app.

## 0.0.5

- Added an ability to use Highstock and Highmaps.
- The addon no longer automatically imports the Highcharts Bower package, letting user import desired package manually.
