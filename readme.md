# speakers [![Build Status][travis-badge]][travis]

Speaker count for 370+ languages.

Painstakingly crawled by hand from [OHCHR][], the numbers are (in
some cases, very) rough estimates or out-of-date.

## Installation

[npm][]:

```bash
npm install speakers
```

## Usage

```js
var speakers = require('speakers');

speakers.eng; //=> 322000000
speakers.jpn; //=> 125000000
speakers.por; //=> 182000000
speakers.cmn; //=> 885000000
```

## API

### `speakers`

Object mapping `string`s (ISO 639-3 codes) to `number`s (speakers).

## License

[MIT][license] © [Titus Wormer][author]

<!-- Definitions -->

[travis-badge]: https://img.shields.io/travis/wooorm/speakers.svg

[travis]: https://travis-ci.org/wooorm/speakers

[npm]: https://docs.npmjs.com/cli/install

[license]: LICENSE

[author]: http://wooorm.com

[ohchr]: http://www.ohchr.org
