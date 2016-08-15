ANTM Revo 7 / AN708
---------------------------------------------

| Item                      | Description |
|---------------------------|-------------|
| Manufacturer              | ANTM USA |
| Device                    | AN708 |
| Website                   | http://.../products/device |
| Vendor driver (Windows)   | ftp://.../(drivers/device/driver.zip) |
| Extracted firmware        | [firmware.fw](firmware.fw) |
| Firmware for gslx680-acpi | [silead_ts.fw](silead_ts.fw) |
| Display resolution        | 1024x600 |
| Touch panel resolution    | The resolution of the touch screen, usually smaller than the display resolution |
| Touch controller          | GSL1860, you should open your device and verify this |
| Multitouch support        | Yes (5) |
| Finger tracking           | Yes, if the chip already does finger tracking, No if software finger tracking needs to be enabled in the driver |
| Mirrored horizontally     | Yes, if the touch screen is mirrored along the X axis, i.e. left and right are reversed, otherwise No |
| Mirrored vertically       | Yes, if the touch screen is mirrored along the Y axis, i.e. top and bottom are reversed, otherwise No |
| Axes swapped              | Yes, if the touch screen is rotated by 90 degrees, i.e. moving from left to right results in movement from top to bottom |
| Comments                  | The exact fwtool command line used to generate silead_ts.fw or other relevant information |
