# @familyjs/prettier-config

Shared Prettier config used in Family, Jigra, and Rindo projects.

## Usage

Usage is based on [Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations) from the Prettier docs.

1. Remove existing `.prettierrc` file, if present.
1. Install the config.

    ```
    npm install -D @familyjs/prettier-config
    ```

1. Add the following to `package.json`:

    ```
    "prettier": "@familyjs/prettier-config",
    ```
