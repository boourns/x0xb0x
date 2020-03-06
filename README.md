#x0xb0x firmware source code

I'm just collecting x0xb0x firmware source codes into a single repo, because they're spread out across various forum threads and hard to nail down which source compiles to which version which gives which features (and contain which bugs).

stock is the latest from sourceforge CVS, thanks a1k0n.

mod is from a Sokkos source zip, I think of sokkos 1.9.1 but may be incorrect.

Both of these firmwares have MIDI timing fixed properly, see https://forums.adafruit.com/viewtopic.php?f=13&t=154923 for details.

The 'mod' firmware will change loaded sequences when receiving MIDI CC #0 (as well as MIDI program change messages).  This is useful for being sequenced from the Octatrack, for example.
