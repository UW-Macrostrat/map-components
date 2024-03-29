# map-components

React components for vector maps. A thin wrapper around d3.js.
This library is similar in structure
to [React Simple Maps](https://www.react-simple-maps.io/examples/usa-with-state-labels/)
but with a enhanced canvas and granular projection support.

**This repository has been archived. It is now part of [Macrostrat's web components monorepo](https://github.com/UW-Macrostrat/web-components).**

## Installation

```
npm install @macrostrat/map-components
```

Include stylesheets into your app from `@macrostrat/map-components/dist/esm/index.css`.

## Changelog

### Summer 2019

- Code created as part of `corelle` project

### December 2019

- Initial vendorization of library for use in column renderer widget

### April 2020

- Complete move towards typescript
- Update bundler strategy

### [0.2.0] August 2020

- Improve typings
- Fix bug with projection clipping and `Sphere` geometry.

### [0.2.1]

- Add better state handling and ability to reset projection.
