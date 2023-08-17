# Ender 3 v2 Klipper config

This is the `printer.cfg` im using with my Creality ender 3 v2 with the following mods:
- Direct Drive Mount
- Dual gear extruder

---

I followed [this](https://www.youtube.com/watch?v=eOURi14SuO0&t=2810s&ab_channel=VictorBared) guide to install Klipper on a `Raspberry Pi 2b` and here are some notes:
- The `START_PRINT` macro load the **default** besh mesh, make sure it exists.
- The values for `z_offset` works on my printer, make sure you re calibrate with `PROBE_CALIBRATE` command
- The values for the `rotation_distance` (eSteps) work on my dual gear extruder, make sure you re calibrate it following [this](https://www.youtube.com/watch?v=8CT9xR3Itks&t=303s&ab_channel=JoePrints) guide.

