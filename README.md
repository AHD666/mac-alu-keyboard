# mac-alu-keyboard - fixing the damn thing
# currently only the german layout - iso version i guess
#
+ layout de
+ Changes to the generic | generic 105-key (intl) PC model. 

- switched: keycode 49 (labeled: ^°) with keycode 94 (labeled: <>)
- changed: 3rd symbol for key <AC09> (labeled: 'L@') from 'stroke' to 'at') 
- changed: symbol for key <CAPS> (the one with the led) to F20
- removed: modifier_map Lock { <CAPS> };
- changed: symbols for <FK13> to <FK19> to F13-F19
- and finnaly switched the caps lock indicator to display the num-lock state

- additionally, if you prefer the alt and cmd (super) key switched, add 'options hid_apple swap_opt_cmd=1' to a modprobe file.
- adding 'fnmode=2' to the line before changes the function key behaviour


