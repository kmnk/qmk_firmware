
## Follow upstream

```
$ git remote add upstream git@github.com:qmk/qmk_firmware.git
$ git fetch upstream
$ git merge upstream/master
```

## Build

```
$ cd keyboards/ergodox_ez
$ make keyboard=ergodox_ez keymap=kmnk_win
```
