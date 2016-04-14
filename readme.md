# vim-json

> JSON parse / stringify

Coming from [vim-rhubarb](https://github.com/tpope/vim-rhubarb), this plugin provides `JSON#parse` and `JSON#stringify` for inclusion in other plugins.

## Install

Install this plugin using your favorite plugin manager, or manually by
extracting the files in your `~/.vim` or `~/.config/nvim` directory.

    Plug 'mklabs/vim-json'

## API

#### JSON#parse

    let data = JSON#parse(json)

Takes `json` string and return the equivalent `data` dictionary.

#### JSON#stringify

    let json = JSON#stringify(dictionary)

Takes `dictionary` and return the `json` representation.

## License

Distributed under the same terms as Vim itself. See :help license
