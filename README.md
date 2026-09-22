ZMK config for the Charybdis Nano on a Canadian Multilingual Standard system

Keymap is edited using [Nick Coutsos' keymap-editor](https://nickcoutsos.github.io/keymap-editor/)

Layout is drawn using [Cem Aksoylar's keymap-drawer](https://github.com/caksoylar/keymap-drawer):

![Layout](documentation/keymap_visual.svg)

## Troubleshooting

After connecting the side(s) you want to troubleshoot to USB, and making sure the LOG variables are set in config/charybdis.conf, run:

```sh
$ ls /dev/ttyACM*
/dev/ttyACM0

$ sudo screen /dev/ttyACM0 115200
```

When done, kill with `Ctrl+A` and then `K`
