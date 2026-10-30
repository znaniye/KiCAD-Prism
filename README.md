# Stale board nets repro

Assets for the KiCad Prism pull request that keeps distinct schematic nets apart on a stale board net.

`repro/` is a two-resistor project whose board is behind its schematic: R1.1 is on `/GND_A` and R2.1 on `/GND_B` in the schematic, but both pads sit on the board net `STALE`.
