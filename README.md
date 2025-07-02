FS8626 and FS872, both from FastSoc's FSFC series. While they share many features, they are optimized for different use cases.
FS8626 is more configurable, supports dual-port fast charging with dynamic power allocation, and suits advanced charging systems.
FS872 is simpler, cost-effective, and ideal for applications that don't require complex power management.

| Feature                                | **FS8626**                                                    | **FS872**                                 |
| -------------------------------------- | ------------------------------------------------------------- | ----------------------------------------- |
| **Package**                            | TSSOP20                                                       | TSSOP20                                   |
| **Type-A Protocol Support**            | BC1.2, Apple 2.4A, QC2.0, QC3.0, FCP, AFC, SCP, Direct Charge | BC1.2, Apple 2.4A, QC2.0, QC3.0, FCP, AFC |
| **Type-C Protocol Support**            | Type-C, PD2.0/3.0/3.2, PPS, QC4                               | Same as FS8626                            |
| **VBUS Regulation Range**              | 3V \~ 21V                                                     | 3V \~ 20V                                 |
| **Voltage Regulation Accuracy**        | 20mV/step                                                     | 20mV/step                                 |
| **Regulation Speed**                   | 20mV/us                                                       | 20mV/us                                   |
| **Max Supported Power (configurable)** | Up to 35W / 20V (e.g., H3 type)                               | Up to 65W / 20V (e.g., type I)            |
| **Dual Port Behavior**                 | Dual-port simultaneous fast charging with power downshift     | Dual-port fallback to 5V shared output    |
| **Custom PDO Support**                 | Yes (via FUNC pins)                                           | Yes (via FUNC pins)                       |
| **Constant Current Mode**              | Not supported                                                 | Not supported                             |
| **D± Voltage Tolerance**               | 13V                                                           | 13V                                       |
| **CC Pin Tolerance**                   | 30V                                                           | 30V                                       |

| Feature                      | FS8626                                                                                            | FS872                                                                                       |
| ---------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Dual-Port Power Strategy** | Supports dual Type-C fast charging with power sharing (e.g., 20W+20W downshift to 15W+15W)        | Automatically falls back to 5V on both ports when both are inserted                         |
| **Best Use Case**            | Ideal for dual-port wall chargers, USB outlets, or power panels requiring flexible output control | Suitable for simpler systems like car chargers or mobile power banks with fewer constraints |

