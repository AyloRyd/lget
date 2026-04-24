# lget

Original repository: [pencelheimer/lget](https://github.com/pencelheimer/lget)

A fast, interactive command-line tool to fetch open-source licenses directly from the [SPDX repository](https://github.com/spdx/license-list-data).

## Run with npx

```bash
npx lget-cli
```

## Or install globally with npm

```bash
npm install -g lget-cli
lget-cli
```

## Usage examples

Run interactively to select a license from a TUI menu:
```bash
npx lget-cli
```

Pass a license directly to bypass the menu:
```bash
npx lget-cli -l mit
```

Force overwrite an existing LICENSE file without prompting:
```bash
npx lget-cli -f -l apache2
```

Suppress all output with the quiet flag:
```bash
npx lget-cli -f -l gpl3 -q
```

## TODO
- Shell completions
- Man page
- TLDR page
