# Oops

## Contributing

The best way to achieve this is together! That's why we are on GitHub. We would love contributions from the community (bug reports, feature requests, suggestions, Pull Requests, whatever you want!).

[Yarn](https://classic.yarnpkg.com/en/docs/cli/) is used as package manager. [Semantic Release](https://semantic-release.gitbook.io/semantic-release/) is used to manage the whole package release workflow.

To setup your local dev environment:

1. Install [Yarn](https://classic.yarnpkg.com/en/docs/install)

2. Clone repository

```sh
git clone git@github.com:ctrlup-io/oops.git
cd oops
```

3. Install dependencies

```sh
yarn install
```

4. See [more available scripts](README.md#scripts)

## Available Scripts

In the project directory, you can run:

### `commit`

Runs the [`git-cz`](https://github.com/streamich/git-cz) CLI to generate commit messages according to the [_Conventional Commit specifications_](https://www.conventionalcommits.org/en/v1.0.0/#specification).

### `lint`

Runs [ESLint](https://eslint.org/) with [standard configuration](https://standardjs.com/).

We recommend to use ESLint in your IDE, e.g. in Visual Studio code with [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

### `format`

Runs [Prettier](https://prettier.io/) with [basic configuration](https://prettier.io/docs/en/configuration.html#basic-configuration).

We recommend to use Prettier in your IDE, e.g. in Visual Studio code with [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode).

### `release:dry`

Runs [Semantic Release](https://semantic-release.gitbook.io/semantic-release/) in dry-run mode. It allows you to preview the pending release.

You have to set `NPM_TOKEN` and `GITHUB_TOKEN` in `.env` file.
