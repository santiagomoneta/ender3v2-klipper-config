# Ender 3 v2 Klipper config

These are the latest files I'm using with my Creality Ender 3 v2 with the following, config impact mods:
- Direct Drive Mount
- Dual gear extruder

---

After following teh Ellis Tune guide I saw that I could set the max_accel up to 14K! but since I print detailed model I leaned to quality over speed and set the value to 2000

---

I use Orca Slicer and there I started from the included Ender 3 V2 profile and modified the following:
- changed flaver from marlin to klipper (duh!)
- first and last gdcode `PRINT_START EXTRUDER=[nozzle_temperature_initial_layer] BED=[bed_temperature_initial_layer_single]` / `PRINT_END`
- Motion ability:
  ![Description](https://i.imgur.com/GWsd8SC.png)
