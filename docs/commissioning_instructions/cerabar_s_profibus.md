# Cerabar S Profibus Device Configuration

#### Manufacturer View
+ Operating Menu
  + Settings
    + Basic Setup
      + Measuring Mode -Pressure
      + Press. Eng. Unit - psi

  + Transmitter Info
    + Transmitter Data
      + Tag Descriptor - PIT-xxx

## Resetting the Device
#### Manufacturer View
+ Operating Menu
  + Operation
    + Insert Pin No
      + 33333 (User Reset)
      + 1 (Total Reset)

## Hardware addressing

1. Unscrew front cover & remove display
1. Set DIP switch 8 (SW/HW) to "Off" (Down) = Hardware Addressing
1. Configure the address with DIP switches 1 to 7.
1. You have to wait 10 seconds for a change in address to take effect. The device is restarted.

|DIP-Switch|1|2|3|4|5|6|7|
|---|---|---|---|---|---|---|---|
|Binary Weighting|1|2|4|8|16|32|64|

### Example

Dip-Switches 3 & 4 "On" (Up) remaining Dip-Switches "OFF"(Down)

Address = 4+8 = 12