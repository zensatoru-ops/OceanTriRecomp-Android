# Android launch cheat selector

The Android activity now displays a cheat-selection dialog after a valid Monster Hunter Tri ROM has been found or copied. The selection is passed to the existing native cheat registry through the repeatable `--cheat <name>` command-line option; no second cheat implementation or memory patch table is introduced.

Available launch toggles:

- No damage
- No action stamina drain
- Infinite items
- Inf gathering
- No knockback
- Infinite health
- Infinite stamina
- 1 hit kills

The default is all cheats off. **Mulai Game** starts with the checked cheats; **Mulai tanpa cheat** starts with none. Choices apply to the current launch only. Online play remains subject to the runtime's existing rule that refuses connections while cheats are enabled.

The selector intentionally exposes only a small set of simple boolean cheats. Cheats requiring a value, button mapping, typed text, or additional configuration remain available through the native `--cheat` interface but are not exposed in this first Android dialog.
