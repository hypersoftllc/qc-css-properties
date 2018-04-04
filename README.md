# @qc/css-properties

[![Build Status][travis-svg]][travis-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]


## Installation

```sh
npm install --save @qc/css-properties
```

or

```sh
yarn add @qc/css-properties
```


## Example Usage


```jsx
import CN from 'classnames'
import React from 'react'

// Use ONE of the following imports
import '@qc/css-properties/src/css-properties.css'
import '@qc/css-properties/dist/styles/css-properties.css'
import '@qc/css-properties/dist/styles/css-properties.min.css'

export default function MyComponent(props) {
  return (
    <div className={CN('MyComponent', 'display-flex', { hidden: !props.show })}>
      ...
    </div>
  )
}
```


## Other Packages from [QC]

* [@qc/react-block][qc-react-block]
* [@qc/react-conditionals][qc-react-conditionals]
* [@qc/react-layer][qc-react-layer]
* [@qc/react-page][qc-react-page]


## Maintainers

- [Danny Hurlburt](https://github.com/dhurlburtusa)


## License

ISC


[downloads-image]: http://img.shields.io/npm/dm/@qc/css-properties.svg
[downloads-url]: http://npm-stat.com/charts.html?package=@qc/css-properties
[license-image]: http://img.shields.io/npm/l/@qc/css-properties.svg
[license-url]: LICENSE
[package-url]: https://npmjs.org/package/@qc/css-properties
[npm-badge-png]: https://nodei.co/npm/@qc/css-properties.png?downloads=true&stars=true
[qc]: https://www.npmjs.com/~qc
[qc-react-block]: https://www.npmjs.com/package/@qc/react-block
[qc-react-conditionals]: https://www.npmjs.com/package/@qc/react-conditionals
[qc-react-layer]: https://www.npmjs.com/package/@qc/react-layer
[qc-react-page]: https://www.npmjs.com/package/@qc/react-page
[travis-svg]: https://travis-ci.org/hypersoftllc/qc-css-properties.svg?branch=master
[travis-url]: https://travis-ci.org/hypersoftllc/qc-css-properties
