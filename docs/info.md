<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This programmable threshold voltage comparator allows comparing a voltage provided externally by the user (Vref) with a voltage level (threshold). The threshold voltage selection is controlled by 3 digital signals, which allow selecting one of the 8 possible threshold voltage levels. 7 of these levels are fixed (from 001 to 111), and only one (000) can be set by the user (in0). The output voltage (out) will be high (1.8V) when the selected threshold voltage is lower than Vref (Vth < Vref); otherwise, it will be low (0V).

## Performance
Rise time of out signal (from 0.2V to 1.6V) is 8.5ns. 
Fall time of out signal (from 1.6V to 0.2V) is 19ns.

Maximum switching frequency of all input signals (even if they switch all at the same time) is 100KHz, i.e. all signals can switch at the same time, but the fastest one MUST NOT exced 100KHz. 

## How to test
VDPWR voltage (supply voltage): 1.8V
VGND voltage (supply voltage): 0V

Vref voltage range (voltage reference for comparison): 0V to 1.8V
in0 voltage range (free voltage threshold): 0V to 1.8V

in[0], in[1], in[2] (digital inputs): 0V (logically 0), 1.8V (logically 1)

Maximum switching frequency of all input signals (even if they switch all at the same time) is 100KHz.


