<div align="center">
  <h1>repo-template</h1>
  <p>Boring GitHub Repository Template</p>

  <div>
    <a href="https://github.com/boringcodes/prod-builder/commits" aria-label="Commitizen Friendly">
      <img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square">
    </a>
    <a href="https://github.com/boringcodes/prod-builder/actions" aria-label="Build Status">
      <img src="https://img.shields.io/github/workflow/status/boringcodes/prod-builder/build-image?style=flat-square">
    </a>
    <a href="https://hub.docker.com/r/boringcodes/prod-builder" aria-label="Docker Image Version">
      <img src="https://img.shields.io/docker/v/boringcodes/prod-builder?color=brightgreen&style=flat-square">
    </a>
    <a href="https://hub.docker.com/r/boringcodes/prod-builder" aria-label="Docker Image Downloads">
      <img src="https://img.shields.io/docker/pulls/boringcodes/prod-builder?color=brightgreen&style=flat-square">
    </a>
    <a href="https://github.com/boringcodes/prod-builder/blob/master/LICENSE" aria-label="MIT License">
      <img src="https://img.shields.io/github/license/boringcodes/prod-builder?color=brightgreen&style=flat-square">
    </a>
    <a href="https://github.com/boringcodes" aria-label="BoringCodes Verified">
      <img src="https://img.shields.io/badge/boringcodes-verified-brightgreen?style=flat-square">
    </a>
  </div>
</div>

## Features

- [x] Alpine NodeJS (10, 12, 14, 15, 16)

## Development

Build node.js alpine images

```bash
  docker build -t boringcodes/prod-builder:node-10-alpine node/10
  docker build -t boringcodes/prod-builder:node-12-alpine node/12
  docker build -t boringcodes/prod-builder:node-14-alpine node/14   # :node-lts-alpine
  docker build -t boringcodes/prod-builder:node-15-alpine node/15
  docker build -t boringcodes/prod-builder:node-16-alpine node/16   # :node-current-alpine
```

## Usage

Example use of `boringcodes/prod-builder:node-current-alpine` to run your node.js app

```bash
  docker run --rm -d -v $PWD:/app boringcodes/prod-builder:node-current-alpine
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors

[BoringCodes](https://github.com/boringcodes)

## License

[MIT](https://github.com/boringcodes/repo-template/blob/master/LICENSE)
