# Ender Modular Mount

This project is an offshoot of the Clock 3 project for Ender 3 and Ender 5 printers. It serves two purposes:

1. Add a modular attachment point to Ender 3 and Ender 5 hotends.
2. Allow the use of V6 hotends in both Bowden and direct drive (with either a BMG or Titan extruder)

This project is part of a larger effort to standardize the connections on my 3D printers for high temperature enclosed printing (up to 60C/140F).

## Hotend Support

| Mk8 Bowden | V6 with BMG |
|------------|-------------|
| [![stock with wiring panel](/Photos/Mk8_Bowden.jpg)](/Photos/Mk8_Bowden.jpg) | [![V6 with BMG extruder](/Photos/V6_direct_drive.jpg)](/Photos/V6_direct_drive.jpg) |

### V6

Most any V6 hotend can be mounted. The cooling duct has several millimeters of play up or down to accomdate different hotend lengths.

Direct drive is supported via either BMG or Titan.

### Mk8

Mk8 hotends can be used in a Bowden configuration with just the wiring panel mount. Direct drive is not supported.

## Connectors

### Hotend

This is a Molex Micro Fit 3.0 connector, which allows up to 5 amps of current. At 60C and bundled in a wiring harness, we allow 50% de-rating. That still allows up to a 60W cartridge heater.

### ABL

For EZABL and any other ABL with multiply-insulated, pre-tailed connector, there is a wiring anchor instead of a connector. For other 5-pin servo-driven ABLs, there is a 5-pin JST SM connector.

### Thermistor, Cooling Fan, Part Fan

All of these have 2-pin JST SM connectors.