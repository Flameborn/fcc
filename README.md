# Fish-currency-converter

This is a port of [Bash Currency Converter](https://github.com/lecler-i/bash-currency-converter), a simple fish script to do currency conversion on the command line.

It uses [XE](https://www.xe.com/) to fetch currency rates.

### Requirements

>fish curl sed

### Installation

The easiest is via [Fisher](https://github.com/jorgebucaran/fisher):

```console
fisher install Flameborn/fcc
```

Update

```console
fisher update Flameborn/fcc
```

### Usage

```bash
fcc 42 EUR USD
42 EUR = 44.2680 USD
```

## License

[MIT](https://github.com/Flameborn/fcc/blob/main/LICENSE)
