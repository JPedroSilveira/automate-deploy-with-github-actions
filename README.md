![](https://github.com/JPedroSilveira/github-actions-v2/workflows/CI/badge.svg?branch=develop&event=push)

# Create a CI/CD workflow for React app

## Setup

Install [node](https://nodejs.org/en/) stable version and execute:

```
npm install
```

## Execute tests

```
npm run test
```

## Development mode

```
npm run start
```

## Production Build

```
npm run build
```

## Commit Message

We are using commitzen to help you with commit creation following your patterns.
Execute:

```
npx commitizen init cz-conventional-changelog --save-dev --save-exact
```

## Quick deploy

You can use Surge for a quick deployment:

1. Install Surge, [click here](https://surge.sh/).
2. Execute:

   ```
   npm run build
   ```

3. Deploy build folder using Surge

## Code Formatting Rules

This project uses [Prettier](https://prettier.io/) to define formatting rules. You can automagically format your code executing:

```
npm run format:write
```

You can also check current code formatting using:

```
npm run format:check
```
