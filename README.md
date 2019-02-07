# Overview

> graphql visualizer

[![NPM](https://img.shields.io/npm/v/graphql-birdseye.svg)](https://www.npmjs.com/package/graphql-birdseye) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

GraphQL Visualizer for better development workflows. Still a **WIP**!

Heavily inspired by [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) and the folks at [Apis-guru](https://github.com/APIs-guru)

## Demo

[![Edit graphql-birdseye-demo](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/xp9mp9rzwo)

## Install

### NPM

```bash
npm install --save graphql-birdseye
```

### Yarn

```bash
yarn add graphql-birdseye
```

## Usage

```text
import * as React from 'react';

import GraphqlBirdseye from 'graphql-birdseye';

class Example extends React.Component {
  render() {
    return <GraphqlBirdseye schema={this.props.schema} />;
  }
}
```

## License

MIT © [novvum](https://github.com/novvum)

Made with ❤️ by [Novvum](https://www.novvum.io)

