# chruby plugin

This plugin loads [`chruby`](HTTPS://GitHub.Com/postmodern/chruby), a tool that
changes the current Ruby version, and completion and a prompt function to
display the Ruby version. Supports brew and manual installation of chruby.

To use it, add `chruby` to the plugins array in your zshrc file:

```zsh
plugins=(... chruby)
```

## 🛠️ Usage

If you'd prefer to specify an explicit path to load chruby from you can set
variables like so:

```zsh
zstyle :omz:plugins:chruby path /local/path/to/chruby.sh
zstyle :omz:plugins:chruby auto /local/path/to/auto.sh
```
