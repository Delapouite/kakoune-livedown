# kakoune-livedown

[kakoune](http://kakoune.org) plugin to live preview markdown files with [livedown](https://github.com/shime/livedown)

## Install

Add `livedown.kak` to your autoload dir: `~/.config/kak/autoload/`.

`livedown` must be installed on your system:

```
$ npm install -g livedown
```

## Usage

`livedown-start` runs a livedown process in the background listening on PORT `livedown_port` option.
Your default browser is launched to display the current buffer file rendered to HTML.

Use `livedown-stop` to kill the background process.

## See also

- [vim-livedown](https://github.com/shime/vim-livedown)
- [markdown.kak](https://github.com/mawww/kakoune/blob/master/rc/base/markdown.kak)

## Licence

MIT
