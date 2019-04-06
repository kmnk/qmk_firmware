
## Follow upstream

```
$ git remote add upstream git@github.com:qmk/qmk_firmware.git
$ git fetch upstream
$ git merge upstream/master
```

## Build

```
$ make keyboard=ergodox_ez keymap=kmnk_win
```
