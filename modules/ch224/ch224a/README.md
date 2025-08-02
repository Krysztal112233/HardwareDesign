## CH224A module

This is a PD protocol deception module, which can be used to deceive with PD supported chargers into outputting a specified voltage for use by subsequent peripherals.

### Note

For configure outputting of a specified voltage, you have to replace the R1 register.

And see the table blow for chosen the value of R1:

|     R1 | Voltage |
| -----: | :------ |
| 6.8k Ω | 9V      |
|  24k Ω | 12V     |
|  56k Ω | 15V     |
| 129k Ω | 20V     |
| 210k Ω | 28V     |
