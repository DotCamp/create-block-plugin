# Wordpress Block Plugin Monorepo by Dotcamp

This template should help you get started with WordPress block plugin development with a pnpm monorepo.

> **Compatibility Note:**
> This block plugin is a pnpm monorepo (workspace) and requires [`pnpm`](https://pnpm.io/).
`npm`/`yarn`/`bun` will not work.

## Start in watch mode
```
$ pnpm run start
```

## Build project
```
$ pnpm run build
```

## Link the plugins to your wordpress installation
For Mac or Linux:
```
$ ln -s <full-path-to-plugin-scaffold-dir>/apps/<plugin-dir> <full-path-to-wp-dir>/wp-content/plugins/
```
For Windows, we recommend using [`junction`](https://learn.microsoft.com/en-us/sysinternals/downloads/junction)
```
$ junction.exe <path-to-plugin-dir> <path-to-wp-dir>/wp-content/plugins/<plugin-dir>
```
Example:
```
# MacOS/Linux
$ ln -s /home/dotcamp/example-plugin/apps/example-plugin /var/www/wp-content/plugins/example-plugin

# Windows
$ junction.exe example-plugin\apps\example-plugin D:\www\wp-content\plugins\example-plugin
```

## Export plugin zip
```
$ pnpm run export
```

