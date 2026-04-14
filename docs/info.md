<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The circuit takes 4 bits A0 A1 B0 and B1 and returns whether or not \[A1:A0\] is greater, equal or less than \[B1:B0\] by lighting one of three LEDs.

## How to test

If \[A1:A0\]<\[B1:B0\], then `A<B` LED should turn on, otherwise if \[A1:A0\]>\[B1:B0\], then `A>B` LED should turn on, if they are equal, then `A=B` turns on.

## External hardware

3 LEDs.
