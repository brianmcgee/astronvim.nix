# AstroNvim.nix

My AstroNvim configuration with Nix!

## Why?

Having my configuration ready as a `flake` allows me to run `nvim` wherever I want!

**Note**: This is a personal configuration tailored to my specific needs. Feel free to fork this repository and customize on your own!

## Setup

### \[Optional\] Add flake registry shortcut

You can add the following registry shortcut to type less characters:

```console
$ nix registry add nvim-aldo github:brianmcgee/astronvim.nix
```

## Running my Astro NeoVim

Just issue the following command:

```console
$ nix run nvim-aldo#astronvim
```

## Acknowledgements

Shamelessly forked from [Aldo Borrero](https://github.com/aldoborrero/astronvim.nix), who took inspiration from the one, the only, [@Mic92](https://github.com/mic92/dotfiles)!

## License

See [License](License) for more information.
