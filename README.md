# branch: use-pure-msys2

This branch was obsolete, because we don't want to use pure MSYS2 and then run `ridk install`.

Instead we will use MSYS2 which is built into the official RubyInstaller2-devkit.


# rbenv for Windows

Manage multiple Rubies on Windows.

<br>

## Install



<br>

## Environment Variables

- `RBENV_ROOT`: Ruby-on-Windows

name | default | description
-----|---------|------------
`RBENV_VERSION` | | Specifies the Ruby version to be used.<br>Also see [`rbenv shell`](#rbenv-shell)
`RBENV_ROOT` | `C:\Ruby-on-Windows` | Defines the directory under which MSYS2, Ruby versions, shims and rbenv itself reside.<br>Also see `rbenv root`
`RBENV_DIR` | `$PWD` | Directory to start searching for `.ruby-version` files.


<br>
