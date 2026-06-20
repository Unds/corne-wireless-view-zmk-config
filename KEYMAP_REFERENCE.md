# Corne Keymap Reference

Hardware: nice!nano v2 + nice!view | OS: Windows | Base layout: **Colemak-DH**

> Generated to match `config/corne.keymap`. 7 layers (0–6). Tap = press & release;
> Hold = press & keep held. Home-row mods only fire when an opposite-hand key is pressed.

---

## Layer Map

| # | Name | How to reach it |
|---|------|-----------------|
| 0 | BASE (Colemak-DH) | default |
| 1 | NUM & SYM | hold right-middle thumb |
| 2 | NAV | hold left-middle thumb |
| 3 | FN & BT | hold right-outer thumb (RAlt), or NUM/NAV + middle thumb |
| 4 | NUMPAD | hold left-inner thumb (Space) |
| 5 | ONE-HAND | **toggle**: NAV layer → top-row 4th key |
| 6 | QWERTY | **toggle**: FN layer → bottom-left key |

To leave a *toggled* layer: One-Hand exits via the left-middle thumb; QWERTY by
re-pressing its toggle key (bottom-left) on the FN layer.

---

## Layer 0 — BASE (Colemak-DH)

```
┌─────┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬──────┐
│ ESC │ Q │ W │ F │ P │ B │   │ J │ L │ U │ Y │ ; │ BSPC │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│ TAB │ A │ R │ S │ T │ G │   │ M │ N │ E │ I │ O │  '   │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│SHFT*│ Z │ X │ C │ D │ V │   │ K │ H │ , │ . │ / │ SHFT │
└─────┴───┴───┴───┴───┴───┘   └───┴───┴───┴───┴───┴──────┘
                ┌─────┬─────┬───────┐   ┌──────────┬─────┬──────┐
                │ GUI │ NAV │ SPACE │   │ ENT/SHFT │ SYM │ RALT │
                └─────┴─────┴───────┘   └──────────┴─────┴──────┘
```
`*` Left Shift (row 3) is **sticky** — tap once, the next key is shifted.

### Home Row Mods (GACS — hold the key for the modifier)

| Hold | Left | | Hold | Right |
|------|------|---|------|-------|
| GUI  | A | | Shift | N |
| Alt  | R | | Ctrl  | E |
| Ctrl | S | | Alt   | I |
| Shift| T | | GUI   | O |

> Left mods only fire when a right-hand key is pressed (and vice versa), so resting
> fingers on home row never triggers a mod. Balanced flavor, 280 ms tapping term.

### Thumbs

| Thumb | Tap | Hold |
|-------|-----|------|
| Left outer  | GUI | GUI |
| Left middle | — | **NAV** (layer 2) |
| Left inner  | Space | **NUMPAD** (layer 4) |
| Right inner | Enter | **Shift** (balanced mod-tap) |
| Right middle| — | **NUM/SYM** (layer 1) |
| Right outer | RAlt | **FN/BT** (layer 3) |

---

## Layer 1 — NUM & SYM (hold right-middle thumb)

Coding-optimized: operators grouped on the left hand, bracket pairs on the right.

```
┌───┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬──────┐
│ ` │ 1 │ 2 │ 3 │ 4 │ 5 │   │ 6 │ 7 │ 8 │ 9 │ 0 │ BSPC │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│ % │ / │ * │ - │ + │ = │   │ ( │ ) │ { │ } │ [ │  ]   │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│ ~ │ ^ │ & │ | │ \ │ _ │   │ ! │ ? │ < │ > │ : │  ;   │
└───┴───┴───┴───┴───┴───┘   └───┴───┴───┴───┴───┴──────┘
          ┌──────┬─────┬─────┐   ┌─────┬──────┬─────┐
          │ CAPS │  —  │  —  │   │  —  │ [FN] │  —  │
          └──────┴─────┴─────┘   └─────┴──────┴─────┘
```
> Right-middle thumb (this layer) + right-outer-mid thumb → **FN/BT** (layer 3).
> `@ # $` are Shift+2/3/4 on the number row above; `"` is Shift+`'` on the base layer.

---

## Layer 2 — NAV (hold left-middle thumb)

```
┌──────┬──────┬──────┬───────┬─────┬─────┐   ┌────────┬──────┬──────┬─────┬─────────┬──────┐
│ PgUp │ PgDn │ C-w  │ 1HAND │ C-t │ C-y │   │ S-Home │ Home │  Up  │ End │  S-End  │ Ins  │
├──────┼──────┼──────┼───────┼─────┼─────┤   ├────────┼──────┼──────┼─────┼─────────┼──────┤
│ C-a  │ C-s  │ A-Tab│  C-f  │CS-Up│CS-Lt│   │ C-Left │ Left │ Down │ Rgt │ C-Right │ S-Up │
├──────┼──────┼──────┼───────┼─────┼─────┤   ├────────┼──────┼──────┼─────┼─────────┼──────┤
│ C-z  │ C-x  │ C-c  │  C-v  │CS-Dn│CS-Rt│   │ S-Tab  │ Tab  │ S-Lt │S-Dn │ S-Right │ APP  │
└──────┴──────┴──────┴───────┴─────┴─────┘   └────────┴──────┴──────┴─────┴─────────┴──────┘
                      ┌─────┬──────┬─────┐   ┌─────┬──────┬─────┐
                      │  —  │ [FN] │  —  │   │ DEL │ BSPC │ ENT │
                      └─────┴──────┴─────┘   └─────┴──────┴─────┘
```
> **1HAND** (top row, 4th key) toggles the One-Hand layer (5). S- = Shift, C- = Ctrl, A- = Alt.
> **Spreadsheet block:** CS-Up/Dn/Lt/Rt (left hand) = Ctrl+Shift+arrows — select (and jump) to the
> edge of a data block. S-Home / S-End select to line start/end.

---

## Layer 3 — FN & BT (hold right-outer thumb / RAlt)

```
┌──────┬────┬────┬───────┬──────┬──────┐   ┌──────┬──────┬──────┬──────┬────────┬─────────┐
│  —   │ F1 │ F2 │  F3   │  F4  │  F5  │   │ BT 0 │ BT 1 │ BT 2 │ BT 3 │ BT CLR │  Vol+   │
├──────┼────┼────┼───────┼──────┼──────┤   ├──────┼──────┼──────┼──────┼────────┼─────────┤
│ CAPS │ F6 │ F7 │  F8   │  F9  │ F10  │   │ Prev │ Play │ Next │ Mute │  Vol-  │    —    │
├──────┼────┼────┼───────┼──────┼──────┤   ├──────┼──────┼──────┼──────┼────────┼─────────┤
│QWERTY│F11 │F12 │ PrtSc │ ScLk │ Brk  │   │ SNIP │  —   │  —   │  —   │   —    │ GUI+Spc │
└──────┴────┴────┴───────┴──────┴──────┘   └──────┴──────┴──────┴──────┴────────┴─────────┘
```
> **QWERTY** (bottom-left) → toggle layer 6. **SNIP** = Win+Shift+S (Snipping Tool).
> BT 0–3 select a Bluetooth profile; BT CLR clears the current one. GUI+Spc = Windows input switch.

---

## Layer 4 — NUMPAD (hold left-inner thumb / Space)

```
┌───┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬──────┬──────┬──────┐
│ — │ — │ — │ — │ — │ — │   │ 7 │ 8 │ 9 │  -   │ LOCK │ BSPC │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼──────┼──────┼──────┤
│ — │ + │ - │ * │ / │ = │   │ — │ 4 │ 5 │  6   │  .   │S-Tab │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼──────┼──────┼──────┤
│ — │ % │ ^ │ ( │ ) │ . │   │ — │ 1 │ 2 │  3   │ ENT  │ Tab  │
└───┴───┴───┴───┴───┴───┘   └───┴───┴───┴──────┴──────┴──────┘
                ┌─────┬─────┬─────┐   ┌─────┬───┬─────┐
                │  —  │  —  │ SPC │   │ ENT │ 0 │  —  │
                └─────┴─────┴─────┘   └─────┴───┴─────┘
```
> **Tab / S-Tab** move to the next/previous cell. **LOCK** (toggle layer 4) keeps the numpad on
> for long data-entry runs — tap to lock, tap again to release. **-** gives one-handed negatives.

---

## Layer 5 — ONE-HAND (toggle: NAV → top-row 4th key)

For use with the right hand on the mouse. Left half is a full nav cluster; right half is inert.
Press the **left-middle thumb** to exit.

```
┌─────┬──────┬──────┬─────┬──────┬──────┐
│ ESC │ Home │  Up  │ End │ PgUp │ PgDn │
├─────┼──────┼──────┼─────┼──────┼──────┤
│ TAB │ Left │ Down │ Rgt │ BSPC │ DEL  │
├─────┼──────┼──────┼─────┼──────┼──────┤
│SHFT │ C-z  │ C-x  │ C-c │ C-v  │ ENT  │
└─────┴──────┴──────┴─────┴──────┴──────┘
      ┌─────┬────────┬───────┐
      │ GUI │ [EXIT] │ SPACE │
      └─────┴────────┴───────┘
```

---

## Layer 6 — QWERTY (toggle: FN → bottom-left key)

```
┌─────┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬──────┐
│ ESC │ Q │ W │ E │ R │ T │   │ Y │ U │ I │ O │ P │ BSPC │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│ TAB │ A │ S │ D │ F │ G │   │ H │ J │ K │ L │ ; │  '   │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│SHFT*│ Z │ X │ C │ V │ B │   │ N │ M │ , │ . │ / │ SHFT │
└─────┴───┴───┴───┴───┴───┘   └───┴───┴───┴───┴───┴──────┘
```
Home-row mods: A=GUI, S=Alt, D=Ctrl, F=Shift | J=Shift, K=Ctrl, L=Alt, ;=GUI.
Thumbs match the base layer (Enter on the right inner here is a plain key, not a mod-tap).

---

## Combos (active on the BASE layer only)

| Press together | Output | Where (Colemak base) |
|----------------|--------|----------------------|
| Q + W | Escape | top row, left |
| W + F | Tab | top row, left |
| S + I | Caps Word | home row, both hands |
| Y + ; | Delete | top row, right |
| C + D | Screenshot (Win+Shift+S) | bottom row, left |
