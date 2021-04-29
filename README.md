# Automation Interview

Automation interview project.

## Getting Started

### Prerequisites

-   Node: `^14.16.0`
-   Javascript: `^ECMAScript 5` OR Typescript: `^4.0.0`
-   Puppeteer: `^6.0.0`

### Installation

```sh
npm install
```

## Objectives

-   To write tests for scenario(s) present on `.feature` file provided at the beginning of test
-   Tests should:
-   1) Be executed using node
-   2) Compatible with 2 sites: "https://www.casinoeuro.com/en/" and "https://www.betsson.com/en" (English market suffices)
-   3) Passing without flakiness
-   BONUS: Tests work and pass on both Desktop and Mobile platforms (via Puppeteer emulator)
-   BONUS: to use Jest for execution and assertions

## F.A.Q.

### Node not found on Mac

-   Run, one by one, these lines:

```sh
sudo rm -f /usr/local/bin/node
```

```sh
sudo rm -f /usr/local/bin/npm
```

```sh
sudo rm -f /usr/local/bin/npx
```

```sh
sudo ln -s $(which node) /usr/local/bin/
```

```sh
sudo ln -s $(which npm) /usr/local/bin/
```

```sh
sudo ln -s $(which npx) /usr/local/bin/
```

## Useful Links

### Puppeteer

-   Repository: https://github.com/Kradirhamik/automation-interview/
-   Node: https://nodejs.org/en/
-   Javascript: https://www.javascript.com/
-   Typescript: https://www.typescriptlang.org/
-   Puppeteer: <https://github.com/puppeteer/puppeteer>
-   Puppeteer API: <https://github.com/puppeteer/puppeteer/blob/v6.0.0/docs/api.md>
