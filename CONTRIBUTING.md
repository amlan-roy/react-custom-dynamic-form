# Contributing

Thanks for your interest in contributing to React Custom Dynamic Form. We're happy to have you here.

Please take a moment to review this document before submitting your first pull request. We also strongly recommend that you check for open issues and pull requests to see if someone else is working on something similar.

If you need any help, feel free to reach out to [Amlan Roy](https://twitter.com/_royamlan_).

## About this repository

- We use [pnpm](https://pnpm.io) for development.
- We use [Parcel](https://parceljs.org/docs/) as our build system.
- We use [changesets](https://github.com/changesets/changesets) for managing releases.

## Structure

This repository is structured as follows:

```
src
└── index.ts

dist
├── main.js
├── module.js
├── types.d.ts
└── ...
```

| Path                  | Description                              |
| --------------------- | ---------------------------------------- |
| `src/index.ts`        | The source of our code.                  |
| `dist`                | The dist file                            |

## Development

### Fork this repo

You can fork this repo by clicking the fork button in the top right corner of this page.

### Clone on your local machine

```bash
git clone https://github.com/your-username/react-custom-dynamic-form.git
```

### Navigate to project directory

```bash
cd react-custom-dynamic-form
```

### Create a new Branch

```bash
git checkout -b my-new-branch
```

### Install dependencies

```bash
pnpm install
```

## Components

When adding or modifying components, please ensure that:

1. You make the changes for every style.
2. You update the documentation.

## Commit Convention

Before you create a Pull Request, please check whether your commits comply with
the commit conventions used in this repository.

When you create a commit we kindly ask you to follow the convention
`category(scope or module): message` in your commit message while using one of
the following categories:

- `feat / feature`: all changes that introduce completely new code or new
  features
- `fix`: changes that fix a bug (ideally you will additionally reference an
  issue if present)
- `refactor`: any code related change that is not a fix nor a feature
- `docs`: changing existing or creating new documentation (i.e. README, docs for
  usage of a lib or cli usage)
- `build`: all changes regarding the build of the software, changes to
  dependencies or the addition of new dependencies
- `test`: all changes regarding tests (adding new tests or changing existing
  ones)
- `ci`: all changes regarding the configuration of continuous integration (i.e.
  github actions, ci system)
- `chore`: all changes to the repository that do not fit into any of the above
  categories

  e.g. `feat(components): add new prop to the avatar component`

If you are interested in the detailed specification you can visit
https://www.conventionalcommits.org/ or check out the
[Angular Commit Message Guidelines](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines).

## Requests for new feature

If you have a request for a new feature, please create an issue on Github. We'll be happy to help you out.