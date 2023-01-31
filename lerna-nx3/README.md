# Lerna Getting Started Example

This repo is a small example of adding Nx to a Lerna-based monorepo via built-in [add-caching](https://lerna.js.org/docs/lerna-and-nx#set-up-1) lerna script.

Watch this [10-minute walkthrough](https://youtu.be/1oxFYphTS4Y) to see how new versions of Lerna work.

This repo contains three packages or projects:

- `header` (a library of React components)
- `footer` (a library of React components)
- `my-app` (an app which depends on both `header` and `footer`)

```
packages/
    header/
        src/
            ...
        package.json
        rollup.config.json
        jest.config.js

    footer/
        src/
            ...
        package.json
        rollup.config.json
        jest.config.js

    my-app/
        src/
            ...
        public/
        package.json

package.json
lerna.json
nx.json
```
