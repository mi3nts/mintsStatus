# Firmware Status

## CANOPY

| Sensor | Status |
|--------|:--------:|
| IPS7100                                   | ✅ |
| PMS7003                                   | 🔵 |
| COZIR-AH-E-1                              | ✅ |
| BME280                                    | ✅ |
| GPS                                       | 🔵 |
| TGS 2611-C00                              | 🔵 |
| SJH5A                                     | 🔵 |
| OPC N3                                    | 🔵 |
| AS7265x                                   | 🔵 |
| LTR390                                    | 🔴 |
| INA219                                    | 🔵 |
| UV Sensor                                 | 🔴 |
| Renke Anemometer                          | 🔴 |

NOTES:
* OPC N3 will probably take some additional time relative to the others; the code we have in the repo is basically just incompatible with the structure for the CANOPY nodes (written in C++ for Arduino systems)
* Going to set up as many sensors to be worked on remote over the break and try to get some done over the winter break. Will continue to update this weekly (each Thursday).

✅ -> Finished!
🔵 -> Needs work / testing
🔴 -> Needs to be written