# unit-synonyms-metric-prefixes

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-metric-prefixes.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-metric-prefixes)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-metric-prefixes/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-metric-prefixes?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-metric-prefixes/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-metric-prefixes)

Metric prefixes synonyms

## Install

    npm i unit-synonyms-metric-prefixes

## Units

All 20 prefixes specified by the [International Bureau of Weights and Measures (BIPM)](https://en.wikipedia.org/wiki/International_Bureau_of_Weights_and_Measures).

See [Metric prefix on Wikipedia](https://en.wikipedia.org/wiki/Metric_prefix).

## Usage

```js
var synonyms = require('unit-synonyms-metric-prefixes').synonyms;

synonyms['k']; // => kilo
synonyms['million']; // => mega
synonyms['tenth']; // => deci
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
