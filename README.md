# bgcolor

Set your terminal background using [Tailwind CSS colors](https://tailwindcss.com/docs/colors). No dependencies.

## Install

```sh
bun install -g bgcolor
```

or

```sh
npm install -g bgcolor
```

## Usage

```sh
bgcolor orange        # defaults to shade 900
bgcolor purple 50
bgcolor teal 950
bgcolor --help        # list colors and shades
bgcolor reset         # restore the terminal's default background
```

Running `bgcolor` without arguments also shows help. Shades range from `50` to `950`.

Try without installing:

```sh
npx bgcolor orange
npx bgcolor reset
```

Requires a Unix-like environment with `sh` and a terminal that supports OSC 11 (set background) and OSC 111 (reset background).

## License

[MIT](LICENSE)
