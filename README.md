# ed480-Ridinghood
This is just for pedagogic purposes.

This is an implementation of the Edwards elliptic curve with a field size of 480.

Note that this implementation will use 32 arch, even though it will have carry
propagation. Refer to this quote:

`so 16x30 won’t work on 32-bit without carry propagation, because there are
less than 4 bits of headroom (2^64 / 2^60, but the input isn’t perfectly
reduced), but the multiplication and reduction produces coefficients as large
as 38.` [1](https://moderncrypto.org/mail-archive/curves/2014/000321.html)


## Disclaimer
This code is provided as is and does not have any warranty, so use it at your
own risk.
This code is still unstable and under constant development so you might want to
wait for a future release in order to use it.
