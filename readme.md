## KBD67 ISO layout

Simple config for the KBD67 (rev2) keyboard. ISO-layout MacOS (SE).

Function-layer only setup for the F-keys and to allow the toggle of the RGB backlight (RGBT) off...

```
Base layer
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───────┬────┐
│Esc│ 1 │ 2 │ 3 │ 4 │ 5 │ 6 │ 7 │ 8 │ 9 │ 0 │ - │ = │ Backsp│Del │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─────┼────┤
│ Tab │ Q │ W │ E │ R │ T │ Y │ U │ I │ O │ P │ Å │ ^ │     │Home│
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┐ Ent├────┤
│ Caps │ A │ S │ D │ F │ G │ H │ J │ K │ L │ Ö │ Ä │ ' │    │PUp │
├────┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴───┴┬───┼────┤
│LSFT│ < │ Z │ X │ C │ V │ B │ N │ M │ , │ . │ - │ RSFT │ ↑ │PDn │
├────┼───┴┬──┴─┬─┴───┴───┴───┴───┴───┼───┴┬──┴─┬─┴──┬───┼───┼────┤
│LCTL│LAlt│LGUI│        Space        │MO1 │RAlt│RCtl│ ← │ ↓ │ →  │
└────┴────┴────┴─────────────────────┴────┴────┴────┴───┴───┴────┘

Function layer
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬────────┬────┐
│§  │F1 │F2 │F3 │F4 │F5 │F6 │F7 │F8 │F9 │F10│F11│F12│        │RGBT│
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬──────┼────┤
│     │   │   │   │   │   │   │   │   │   │   │   │   │      │    │
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴─┐    ├────┤
│      │   │   │   │   │   │   │   │   │   │   │   │    │    │    │
├────┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴────┴┬───┼────┤
│    │   │   │   │   │   │   │   │   │   │   │   │       │VAI│    │
├────┼───┴┬──┴─┬─┴───┴───┴───┴───┴───┼───┴┬──┴─┬─┴──┬────┼───┼────┤
│    │    │    │                     │TRNS│    │    │RMOD│VAD│MOD │
└────┴────┴────┴─────────────────────┴────┴────┴────┴────┴───┴────┘
```

## Setup/installation

1. Visit https://config.qmk.fm/, select your keyboard and upload the JSON-file – make any edits you wish.
2. Compile and download the firmware.
3. [Follow the instructions for the QMK Toolbox](https://docs.qmk.fm/#/configurator_step_by_step).

## Notes

To flash the KBD67 and to get it to be recognized in QMK Toolbox, just hold down the ESC-key while connecting it you Mac.

© 2021 [Marcus Olsson](https://marcusolsson.me).
