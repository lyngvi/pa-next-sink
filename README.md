Switch between sinks and sources in PulseAudio with a key-press! This tool selects the "next" source or sink from PulseAudio's list, and sets it as the default. The new selection is confirmed with a desktop notification.

You might find this useful if:
* You are running in a Linux desktop environment
* You have multiple audio devices that they need to swap between frequently, such as a USB headset and external speakers

Expected usage:

1. Download `pa-next-sink` to `/usr/local/bin`
2. Create a "next sink" keybinding. Example: Bind `Super-S`, to `/usr/local/bin/pa-next-sink`
3. Create a "next source" keybinding. Example: Bind `Super-Shift-S` to `/usr/local/bin/pa-next-sink --mode source --quiet`
4. Mash `Super-S` when you want to swap from headset to speakers, or vice-versa.