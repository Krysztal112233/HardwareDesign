# DCDC module based TLV62569

This module use [TLV62569](https://www.ti.com/cn/lit/ds/symlink/tlv62569.pdf?ts=1731897045890&ref_url=https%253A%252F%252Fitem.szlcsc.com%252F) as it's **_Step-Down_** voltage regulator.

But you can use any other pin-compatible chip on it :)

## Protection

In this module, I'm using `SMAJ17A` TVS as it's protection. If you wanna higher voltage input, you can use other TVS instead of `SMAJ17A`
