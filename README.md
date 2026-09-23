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

To capture logs to file, press `Ctrl+A` and then `H`, and then `Ctrl+A` and then `H` again to stop capturing logs. It makes it easier to isolate your logs if you use other hardware to do unrelated tasks while capturing logs (e.g., laptop keyboard/trackpad to select windows).

When done, kill with `Ctrl+A` and then `K`
