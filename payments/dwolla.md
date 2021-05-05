# Dwolla

## `.env`

Requirements:

* All repositories _must_ include a `.env` file in the root of the `main` branch. This file should include all of the items:

```
key
Secret

```

* You can obtain a Dwolla Sandbox API Key and Secret by signing up for a free [Dwolla Sandbox Account](https://accounts-sandbox.dwolla.com/login)

## `.gitignore`

Requirements:

* All repositories _must_ include a `.gitignore` file in the root of the `main` branch. This file should include all of the items:

```
.env

```

Rationale:

* Your .env file will contain sensitive information like your Dwolla key and secret, which should never be shared.

Exceptions:

* None
