# Flippy

> A GitHub App built with [Probot](https://github.com/probot/probot) that A Github bot designed to help assist with the day to day tasks of running Flipping Industries

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t Flippy .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> Flippy
```

## Contributing

If you have suggestions for how Flippy could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 Flipping Industries <flippingindustries@gmail.com>
