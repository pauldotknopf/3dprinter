https://docs.vorondesign.com/build/software/octopus_klipper.html

# Cura

## Start gcode

```
; M190 S{material_bed_temperature_layer_0}
; M109 S{material_print_temperature_layer_0}
start_print BED_TEMP={material_bed_temperature_layer_0} EXTRUDER_TEMP={material_print_temperature_layer_0}
```