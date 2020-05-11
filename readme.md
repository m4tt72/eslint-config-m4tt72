# Custom ESLint Config

My personal config for ESLint and Prettier

## Installation

1. jWe need to install everything needed by the config:

```bash
npx install-peerdeps --dev eslint-config-m4tt72
```

2. You can see in your package.json there are now a big list of devDependencies.

3. Create a .eslintrc file in the root of your project's directory (it should live where package.json does). Your .eslintrc file should look like this:

```bash
{
  "extends": [
      "m4tt72"
    ]
}
```

