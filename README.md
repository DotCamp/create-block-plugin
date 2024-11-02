# create-block-plugin

Modelled after [`create-vite`](https://github.com/vitejs/vite)

> **Compatibility Note:**
> This block plugin is a pnpm monorepo (workspace) and requires [`pnpm`](https://pnpm.io/).
`npm`/`yarn`/`bun` will not work.

## Scaffolding Your Wordpress Block Plugin

```
$ pnpm create @dotcamp/block-plugin@latest
```

Then follow the prompts!

You can also specify the project name via command line options as shown below.

```
$ pnpm create @dotcamp/block-plugin@latest my-awesome-plugin
```

# Features
* Monorepo used to manage packages so multiple versions of a plugin (e.g. free and premium) can be developed easily with code sharing.
* Typescript configured out of box.
* Some missing types added and incorrect types fixed.
* Recursive build and watch scripts (no more `concurrently` needed)
* Easy plugin zip export script using `wp-scripts` (more complex plugin export script coming soon)
* Useful scripts for managing monorepo (coming soon)
* Flexible structure - the scaffold is very minimal so the structure can easily be changed, updated, modified to suit the plugin's needs.

