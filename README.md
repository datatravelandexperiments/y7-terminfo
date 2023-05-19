# y7 terminfo

Terminfo initialization for
[y7](https://codeberg.org/datatravelandexperiments/y7).

Sets `$TERMINFO` if a suitable location exists.

Checks, in order:

- the current value of `$TERMINFO`, if any;
- under `$HOME/.terminfo`;
- under `$XDG_DATA_HOME` or `$XDG_DATA_DIRS`;
- under `$XDG_CONFIG_HOME` (terminfo doesn't really belong here but some
  people might use it).
