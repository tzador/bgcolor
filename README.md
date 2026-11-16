# setbg

Set your terminal background using [Tailwind CSS colors](https://tailwindcss.com/docs/colors). No dependencies.

## Install

```sh
bun install -g setbg
```

or

```sh
npm install -g setbg
```

## Usage

```sh
setbg orange        # defaults to shade 900
setbg purple 50
setbg teal 950
setbg --help        # list colors and shades
unsetbg             # restore the terminal's default background
```

Running `setbg` without arguments also shows help. Shades range from `50` to `950`.

Try without installing:

```sh
npx --package=setbg setbg orange
npx --package=setbg unsetbg
```

Requires a Unix-like environment with `sh` and a terminal that supports OSC 11 (set background) and OSC 111 (reset background).

## License

[MIT](LICENSE)
