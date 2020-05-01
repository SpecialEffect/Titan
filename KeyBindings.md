
Current list of available key bindings via the `ConsoleController.gpc` script:

## Stick controls

| Key           | Function      | Note  |
|:-------------:| ------------- | ----- |
| `w`,`b`,`g`,`h`     | Hold left stick 100% forward, backward, left, right | Cancel with `e` |
| `y`,`z`,`c`,`r`     | Hold left stick 50% forward, backward, left, right | Cancel with `e` |
| `e`     | Left stick neutral (i.e. cancel any holds) | |
| `u`      | toggle 'use left stick as face buttons'      |  Cancel by toggling, or with `NumPad1` to reset sticks |
| `d`      | toggle 'use right stick as face buttons'      |  Cancel by toggling, or with `NumPad1` to reset sticks |
| `a`      | swap sticks      |  Cancel by toggling, or with `NumPad1` to reset sticks |
| `7`      | toggle legacy/tank mode. Only one stick will function in this mode, (right stick unless swapped)   |  Cancel by toggling, or with `NumPad1` to reset sticks |
| `NumPad1`      | Reset stick interpretation  | Turns off swap sticks, legacy mode and 'use stick as face buttons' |


## Basic keys

These are defined in `const uint8 map[] = { ... }` in ConsoleController.gpc.

| Key |  PS4 | XB1 | NS | PS3 | XB360 |  Wii
|:---:| --- | --- | --- | --- | --- | --- |
| `x` | cross | A | B | cross | A | B |
| `o` | circle | B | A | circle | B | A |
| `s` | square | XB1 | Y | square | XB360 | Y |
| `t` | triangle | Y | X | triangle | Y | X |
| `1` | R1 | RB | R | R1 | RB | R |
| `2` | R2 | RT | ZR | R2 | RT | ZR |
| `3` | R3 | RS | RS | R3 | RS | SR / Two |
| `4` | L1 | LB | L | L1 | LB | L / C |
| `5` | L2 | LT | ZL | L2 | LT | ZL / Z |
| `6` | L3 | LS | LS | L3 | LS | SL / One |
| `Up` | Dpad Up | Dpad Up | Dpad Up | Dpad Up | Dpad Up | Dpad Up |
| `Right` | Dpad Right | Dpad Right | Dpad Right | Dpad Right | Dpad Right | Dpad Right |
| `Down` | DPad Down  | DPad Down  | DPad Down  | DPad Down  | DPad Down  | DPad Down  |
| `Left` | Dpad Left | Dpad Left | Dpad Left | Dpad Left | Dpad Left | Dpad Left |
| `p` | Touch click | View | Minus | Select | Back | Minus |
| `i` | Options | Menu | Plus | Start | Start | Plus |
| `f` | PS  | Xbox  | Home | PS  | Guide  | Home |

## TODO: still need documenting
- Combos : keys to start, record and repeat combos.  
- rapid fire
- hold state
- short/long hold detection

