# Digital-Clock
It is a 24-Hour Digital Clock made using dsch2 software.

When the enable signal is applied to the Mod 60 counter it generates counts form
0-59 ( seconds ). Once the counter reaches 59 the counter resets to 0 and the CO of
the Mod 60 counter is given as input enable to the 2" Mod 60 counter and it also
generates counts from 0-59( indicating minutes ).

When the minutes counter reaches 59 the counter resets to 0 and CO of the 2" Mod
60 counter is given as input enable to the Mod 24 counter.

The mod 24 counter generates count from 0-24 indicating hours .when the counter
reaches count 23 the counter resets to 0 and the whole process starts all over again.
