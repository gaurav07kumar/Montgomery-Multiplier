Me and my collegue Vignesh Kenche designed a 8-bit Montgomery Modular Multiplier mod 255 using static CMOS. 
It perform (A*B) mod M without using standard expensive division operation. 
This method is typically used in modern cryptograph like RSA.
CMOS circuit is implemented on Cadence Virtuoso designing modules like Carry-Select adder, 4-bit array multiplier.
Total transistor count = 6332, Delay = 6.9169 nS, Peak Power = 14.179 mW
