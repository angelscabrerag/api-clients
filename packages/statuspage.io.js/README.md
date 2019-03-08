# statuspage.io.js [![npm version](https://img.shields.io/npm/v/statuspage.io.svg?style=flat)](https://www.npmjs.com/package/statuspage.io)

A [statuspage.io](https://statuspage.io) API client. For a documentation on the API see https://doers.statuspage.io/.

## Usage

A complete documentation is available at https://ffflorian.github.io/statuspage.io.js/.

### Installation

Run `yarn add statuspage.io` or `npm install statuspage.io`.

### Example

```ts
import {StatusPage} from 'statuspage.io';

const statusPage = new StatusPage('https://example.com');

statusPage.api.incidents.getAll().then(response => {
  //
});
```

## Build and test

```
yarn
yarn test
```