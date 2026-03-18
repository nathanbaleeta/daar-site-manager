# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project including [Strapi Cloud](https://cloud.strapi.io). Browse the [deployment section of the documentation](https://docs.strapi.io/dev-docs/deployment) to find the best solution for your use case.

```
yarn strapi deploy
```

### Set the environment variables locally
In your project's .env file, set environment variables locally by adding unique, strong, randomly generated strings for the following:
- APP_KEYS="toBeModified1,toBeModified2"
- API_TOKEN_SALT=tobemodified
- ADMIN_JWT_SECRET=tobemodified
- TRANSFER_TOKEN_SALT=tobemodified
- JWT_SECRET=tobemodified
- ENCRYPTION_KEY=tobemodified

You can generate one using Node.js with a command like `node -e "console.log(crypto.randomBytes(16).toString('base64'))".`


