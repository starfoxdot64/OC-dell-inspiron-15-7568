# Inspiron 15-7568 OpenCore Folder

Please be sure to use proper tools when editing these files. I used OC Auxilliary Tools, but your mileage can (and likely will) vary.
Be aware that if you found this via the Hackintosh Discord server, you may not receive support because of this.
Pleae also be aware that this is effectively a snapshot, and you may need kext updates. 

This was set up with OpenCore version 0.8.4, confirmed working as of January.

Use your own serial, don't be weird. Bluetooth is bugged on Monterey and later from my knowledge (thanks Intel), and sleep makes this laptop unhappy sometimes. 


# Troubleshooting, as of 6/20/2023

- Keyboard and mouse not responding on wake
  - This seems to be a hinge thing, so try flipping it into tablet mode for a minute, then flipping it back to laptop mode. Linux has similar issues, weirdly, but closing it and opening it sometimes unlocks the keys.
