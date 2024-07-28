# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```

```
Error

Error
Message

When using Node.js version 20 or newer, the scaffolder backend plugin requires that it be started with the --no-node-snapshot option. 
        Please make sure that you have NODE_OPTIONS=--no-node-snapshot in your environment.
```

```
export NODE_OPTIONS=--no-node-snapshot
```

```
add in packages/backstage/src/index.ts
// github
backend.add(import('@backstage/plugin-scaffolder-backend-module-github'));
```

```
publish:github:pull-request
```