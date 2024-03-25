# Stripe Integration Web

Stripe Integration POC

## Installation

navigate to `node` directory
```
cd node
```

install required packages
```
npm install
```

## Setting up keys
Copy values from `.env.template` to `.env`.

From the project `Root` directory, run:
```
cp .env.template .env
```

Get your `publishable` and `secret` keys from your stripe account and paste it on `.env` file.
```
STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```

## Running the app
To start the app run:
```
node node/server
```

## License

[MIT](https://choosealicense.com/licenses/mit/)