# @okisdev/config

Personal configuration for linting and formatting.

## Installation

```bash
pnpm add -D @okisdev/config @biomejs/biome ultracite
```

## Usage

### Biome

Create a `biome.jsonc` in your project root:

```jsonc
{
  "$schema": "./node_modules/@biomejs/biome/configuration_schema.json",
  "extends": ["@okisdev/config/biome"]
}
```

Then run:

```bash
biome check .
biome check --fix .
```

## License

MIT
