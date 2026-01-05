# Gyruss Bootleg Konami-1 CPU

This is a bootleg Konami-1 encrypted CPU daughterboard found on a booleg
Gyruss pcb.

I have drawn out the schematic in Kicad format. A PDF of the schematic, and
a picture of the original board is in the docs directory.

The original board had the ICs soldered directly to the board, I have added
sockets to it during my attempt at fixing it.

The pals directory contains brute-force dumps of the PAL12L6 and the
PAL16L8. Unfortunately the 82S153 on my board appears to be dead.

Change history:  
2026-01-05 - Initial version  

To Do:  
- Create GAL JEDEC files for the two dumped PALs  
- Recreate a new GAL for the missing 82S153  

Marc Deslauriers
