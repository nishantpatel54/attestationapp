# attestation-app

> A GitHub App built with [Probot](https://github.com/probot/probot) that Github app to do attestation for DB changes

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
docker build -t attestation-app .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> attestation-app
```

## Contributing

If you have suggestions for how attestation-app could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2024 Nishant Patel
