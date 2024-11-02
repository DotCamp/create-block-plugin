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

## Why should you use this plugin scaffold?
The main reason you should choose this plugin scaffold as the starting point for
your next WordPress block plugin is because this scaffold takes care of the
busywork, configuration of the monorepo, typescript etc.

A pnpm workspace can be a bit confusing for beginners to set up.
This scaffold takes care of that as well.

It does all this all while not enforcing any non standard patterns or tools.

The configurations are also sensible defaults and should be fine for most use cases.

Best of all, it's all easily modifiable and not hidden behind a tool in a separate
package.

Below are some more features of this scaffold to consider:
* Monorepo used to manage packages so multiple versions of a plugin (e.g. free and premium) can be developed easily with code sharing.
* Typescript configured out of box.
* Some missing types added and incorrect types fixed.
* Recursive build and watch scripts (no more `concurrently` needed)
* Easy plugin zip export script using `wp-scripts` (more complex plugin export script coming soon)
* Useful scripts for managing monorepo (coming soon)
* Flexible structure - the scaffold is very minimal so the structure can easily be changed, updated, modified to suit the plugin's needs.

