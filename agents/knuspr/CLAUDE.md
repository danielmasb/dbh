# Knuspr Agent

This agent automates grocery ordering on [Knuspr](https://www.knuspr.de).

## Capabilities

- Browse and search products
- Add items from `favourites.json` to the cart
- Place orders based on configured preferences

## Configuration

See `config.json` for delivery and account settings.  
See `favourites.json` for the list of regularly ordered products.

## Credentials

Set `KNUSPR_EMAIL` and `KNUSPR_PASSWORD` in the root `.env` file (copy from `.env.example`).
