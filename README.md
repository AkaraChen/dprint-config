# dprint-config

Just my dprint configs.

## Usage

```
pnpm add -D dprint
```

And create a `dprint.json` file, with the following content:

```json
{
    "$schema": "https://dprint.dev/schemas/v0.json",
    "extends": ["..."]
}
```

Replace `...` with the URL of the config you want to use.

## Configs

1. [Web](./src/web.json)
2. [Python](./src/python.json)
3. [Rust](./src/rust.json)
4. [Markdown](./src/markdown.json)
5. [YAML](./src/yaml.json)
