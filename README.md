mp2
===

compile with 

<PRE>
make mp2
(or)
gcc -O3 -lm -o mp2 mp2.c
</PRE>
For unix set USE_TIME
For turbo C - comment out USE_TIME
<PRE>
Notes on test
-------------
Precision is double
Calculation is an harmonic solution to the position of the moon
Comparitive figures: (per cpu)
  10 MHz XT (no 87)    :      1.0
  12 MHz AT 286        :      3.0
  4.77 MHz XT +87      :      8.0
  486DX2-66MHz         :    970.0
  Sun Station10/50 MHz :   2000.0
  100 MHz Pentium      :   3900.0
  433 MHz Celeron      :  16400.0
  Raspberry Pi 3   -O3 :  45000.0 *4
  i5 2.6GHz Lenova -O3 : 122000.0 *4
</PRE>
