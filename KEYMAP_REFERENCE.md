# Corne Keymap Reference

Hardware: nice!nano v2 + nice!view | OS: Windows

---

## Layer Access

| Action | Result |
|--------|--------|
| Hold middle-left thumb | NAV (layer 2) |
| Hold right thumb | NUM/SYM (layer 1) |
| Hold Space | Numpad (layer 4) |
| Hold RAlt | FN/BT (layer 3) |
| NAV + R | Toggle One-Hand (layer 5) |
| FN + bottom-left key | Toggle Colemak-DH (layer 6) |

---

## Layer 0 — BASE (QWERTY)

```
┌─────┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬──────┐
│ ESC │ Q │ W │ E │ R │ T │   │ Y │ U │ I │ O │ P │ BSPC │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│ TAB │ A │ S │ D │ F │ G │   │ H │ J │ K │ L │ ; │  '   │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│SHFT │ Z │ X │ C │ V │ B │   │ N │ M │ , │ . │ / │ SHFT │
└─────┴───┴───┴───┴───┴───┘   └───┴───┴───┴───┴───┴──────┘
                ┌─────┬─────┬───────┐   ┌─────┬─────┬──────┐
                │ GUI │ NAV │ SPACE │   │ ENT │ SYM │ RALT │
                └─────┴─────┴───────┘   └─────┴─────┴──────┘
```

### Home Row Mods (hold the key for the modifier)

| Key | Tap | Hold |
|-----|-----|------|
| A | A | GUI |
| S | S | Alt |
| D | D | Ctrl |
| F | F | Shift |
| J | J | Shift |
| K | K | Ctrl |
| L | L | Alt |
| ; | ; | GUI |

> Left HRMs only fire with right-hand keys pressed, and vice versa (prevents accidental activation).
> Left Shift is sticky — tap once, next key is shifted.

---

## Layer 1 — NUM/SYM (hold right thumb)

```
┌───┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬───┐
│ ` │ 1 │ 2 │ 3 │ 4 │ 5 │   │ 6 │ 7 │ 8 │ 9 │ 0 │ ? │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼───┤
│ $ │ ! │ @ │ # │ $ │ % │   │ = │ ( │ ) │ [ │ ] │ : │
├───┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼───┤
│ * │ \ │ | │ ' │ ~ │ " │   │ - │ + │ { │ } │ - │ 0 │
└───┴───┴───┴───┴───┴───┘   └───┴───┴───┴───┴───┴───┘
          ┌─────┬─────┬─────┐   ┌─────┬──────┬─────┐
          │  —  │  —  │  —  │   │  —  │ [FN] │  —  │
          └─────┴─────┴─────┘   └─────┴──────┴─────┘
```
> Hold right thumb + middle right thumb = FN/BT layer

---

## Layer 2 — NAV (hold middle-left thumb)

```
┌──────┬──────┬──────┬───────┬──────┬──────┐   ┌──────────┬──────┬──────┬─────┬──────────┬─────┐
│ PgUp │ PgDn │ C-w  │ 1HAND │ C-t  │ C-y  │   │ S-Home   │ Home │  Up  │ End │  S-End   │ Ins │
├──────┼──────┼──────┼───────┼──────┼──────┤   ├──────────┼──────┼──────┼─────┼──────────┼─────┤
│ C-a  │ C-s  │ A-Tab│  C-f  │  [   │  ]   │   │ C-Left   │ Left │ Down │ Rgt │  C-Right │S-Up │
├──────┼──────┼──────┼───────┼──────┼──────┤   ├──────────┼──────┼──────┼─────┼──────────┼─────┤
│ C-z  │ C-x  │ C-c  │  C-v  │  <   │  >   │   │  S-Tab   │ Tab  │ S-Lt │S-Dn │  S-Right │ APP │
└──────┴──────┴──────┴───────┴──────┴──────┘   └──────────┴──────┴──────┴─────┴──────────┴─────┘
                      ┌─────┬──────┬─────┐   ┌─────┬──────┬─────┐
                      │  —  │ [FN] │  —  │   │ DEL │ BSPC │ ENT │
                      └─────┴──────┴─────┘   └─────┴──────┴─────┘
```
> **1HAND** = toggle One-Hand layer (layer 5)
> S- = Shift, C- = Ctrl, A- = Alt

---

## Layer 3 — FN/BT (hold RAlt, or NAV/SYM + middle thumb)

```
┌─────┬────┬────┬────┬────┬────┐   ┌──────┬──────┬──────┬──────┬────────┬───────┐
│  —  │ F1 │ F2 │ F3 │ F4 │ F5 │   │ BT 0 │ BT 1 │ BT 2 │ BT 3 │ BT CLR │ Vol+  │
├─────┼────┼────┼────┼────┼────┤   ├──────┼──────┼──────┼──────┼────────┼───────┤
│  —  │ F6 │ F7 │ F8 │ F9 │F10 │   │ Prev │ Play │ Next │ Mute │  Vol-  │   —   │
├─────┼────┼────┼────┼────┼────┤   ├──────┼──────┼──────┼──────┼────────┼───────┤
│  —  │F11 │F12 │PrtSc│ScLk│Brk│   │  —   │  —   │  —   │  —   │   —    │GUI+Spc│
└─────┴────┴────┴────┴────┴────┘   └──────┴──────┴──────┴──────┴────────┴───────┘
```
> BT 0–3 = select Bluetooth profile | BT CLR = clear current profile
> GUI+Spc = Windows language/input switch

---

## Layer 4 — NUMPAD (hold Space)

```
┌─────┬─────┬─────┬─────┬─────┬─────┐   ┌───┬───┬───┬──────┬─────┬─────┐
│  —  │  —  │  —  │  —  │  —  │  —  │   │ 7 │ 8 │ 9 │ BSPC │  —  │  —  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├───┼───┼───┼──────┼─────┼─────┤
│  —  │  +  │  -  │  *  │  /  │  =  │   │ — │ 4 │ 5 │  6   │  .  │  —  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├───┼───┼───┼──────┼─────┼─────┤
│  —  │  %  │  ^  │  (  │  )  │  .  │   │ — │ 1 │ 2 │  3   │ ENT │  —  │
└─────┴─────┴─────┴─────┴─────┴─────┘   └───┴───┴───┴──────┴─────┴─────┘
                    ┌─────┬─────┬─────┐   ┌─────┬───┬─────┐
                    │  —  │  —  │ SPC │   │ ENT │ 0 │  —  │
                    └─────┴─────┴─────┘   └─────┴───┴─────┘
```

---

## Layer 5 — ONE-HAND (toggle with NAV + R)

For use with right hand on mouse. Press middle-left thumb to exit.

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

## Layer 6 — COLEMAK-DH (toggle with FN + bottom-left)

```
┌─────┬───┬───┬───┬───┬───┐   ┌───┬───┬───┬───┬───┬──────┐
│ TAB │ Q │ W │ F │ P │ B │   │ J │ L │ U │ Y │ ; │ BSPC │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│ ESC │ A │ R │ S │ T │ G │   │ M │ N │ E │ I │ O │  '   │
├─────┼───┼───┼───┼───┼───┤   ├───┼───┼───┼───┼───┼──────┤
│SHFT │ Z │ X │ C │ D │ V │   │ K │ H │ , │ . │ / │ SHFT │
└─────┴───┴───┴───┴───┴───┘   └───┴───┴───┴───┴───┴──────┘
```

Home row mods: A=GUI, R=Alt, S=Ctrl, T=Shift | N=Shift, E=Ctrl, I=Alt, O=GUI

---

## Combos

| Keys (simultaneous) | Output | Position |
|---------------------|--------|----------|
| Q + W | Escape | Top row, left |
| W + E | Tab | Top row, left |
| F + J | Caps Word | Home row, both hands |
| I + O | Delete | Top row, right |
| V + B | Screenshot (Win+Shift+S) | Bottom row, left |

---

## Thumb Keys Summary

```
        [ GUI ]  [ NAV ]  [ SPC→Numpad ]     [ ENT ]  [ SYM ]  [ RALT→FN ]
```

| Thumb | Tap | Hold |
|-------|-----|------|
| Left outer | GUI | GUI |
| Left middle | — | NAV layer |
| Left inner | Space | Numpad layer |
| Right inner | Enter | — |
| Right middle | — | NUM/SYM layer |
| Right outer | RAlt | FN/BT layer |
