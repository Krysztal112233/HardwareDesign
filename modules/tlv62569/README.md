# DCDC step-down voltage module based TLV62569

This module use [TLV62569](https://www.ti.com/cn/lit/ds/symlink/tlv62569.pdf?ts=1731897045890&ref_url=https%253A%252F%252Fitem.szlcsc.com%252F) as it's **_Step-Down_** voltage regulator.

But you can use any other pin-compatible chip on it :)

## Protection

This module using `SMAJ17A` TVS as it's protection. If you wanna higher or lower voltage protection, you can use other TVS instead of `SMAJ17A`.

## Notes

### Can I use any other convert?

Yes, of course! This module compatible with any other DCDC voltage step-down converter who use `SOT23-5` footprint.

But you have to redesign of the resistor and capacitor's value.
