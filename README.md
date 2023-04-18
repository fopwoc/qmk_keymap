# Personal keymap

My personal qmk firmware keymap for GMMK pro rev1

```bash
qmk cd && cd keyboards/gmmk/pro/rev1/ansi/keymaps/ && mkdir fopwoc

git clone https://github.com/fopwoc/qmk_keymap/ fopwoc

qmk flash -kb gmmk/pro/rev1/ansi -km fopwoc
```
