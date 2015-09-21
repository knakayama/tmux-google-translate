tmux-google-translate
=====================

Translate word(s) with [Google Translate](https://translate.google.com/)

# Description

**Note:** This code is heavily inspired by [tmux-open](https://github.com/tmux-plugins/tmux-open).

Just do translate.

# Requirements

* [tmux](https://tmux.github.io/)
* [tpm](https://github.com/tmux-plugins/tpm)
* [translate-shell](https://github.com/soimort/translate-shell)

# Install

Install tpm and add the following line to your `~/.tmux.conf`.

```bash
set-option -g @plugin 'knakayama/tmux-google-translate'
```

then, press `Prefix + I` in tmux session.

# Usage

Default key binding translating word(s) is `Prefix + t`. If you want to change this key binding, set the following line to your `~/.tmux.conf`.

```bash
set-option -g @translate-shell-key 'x' # or your favorite key binding
```

Default key binding translating word(s) in copy mode is `T`. If you want to change this key binding, set the following line to your `~/.tmux.conf`.

```bash
set-option -g @translate-copy-key 'X' # or your favorite key binding
```

# License

MIT

# Author

[knakayama](https://github.com/knakayama)

# TODO

- [ ] Option selection
