# CG3

BSELGAL

~~~
python.exe .\gal22v10parse.py ..\CG3\BSELGAL\bselgal_readback.jed "BCAS !DBEN !RAMEN DBCAS !LWR !BITMODE BS2 BS1 BS0 P10 P11 CPUADD BIT7 BIT6 BIT5 BIT4 BIT3 BIT2 BIT1 BIT0 !RAMRD !RAMWR" bselgal 1 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\BSELGAL\bselgal.pld
~~~

DATAGAL

~~~
python.exe .\gal22v10parse.py ..\CG3\DATAGAL\datagal_readback.jed "BCAS !RAMWR !RAMRD OVR7 OVR6 OVR5 OVR4 OVR3 OVR2 OVR1 OVR0 BIT P7 P6 P5 P4 P3 P2 P1 P0 BD BDX" datagal 1 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\DATAGAL\datagal.pld
~~~

IOGAL2

~~~
python.exe .\gal22v10parse.py ..\CG3\IOGAL2\iogal2_readback.jed "CA DBCAS L512 LA1 LA3 LA0 !VRAM !IOSEL LA4 LA2 !LP1SEL LADD1 CPUADD DBEN !RAMEN S2 S1 S0 !XDN !XUP !YDN !YUP" iogal2 2 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\IOGAL2\iogal2.pld
~~~

LINEGAL4

~~~
python.exe .\gal22v10parse.py ..\CG3\LINEGAL\linegal4_readback.jed "DDCLK DOTCLK P3 P4 CPUADD P6 BC4 BC5 BC3 BC2 HBLANK !PALEN !PLOAD !SHIFT !PLOAD P17 P18 P19 P20 !FIFOR !FIFOMR FIFOW" linegal4 4 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\LINEGAL\linegal4.pld
~~~

OUTPUT4

~~~
python.exe .\gal22v10parse.py '..\CG3\OUTPUT\output4_readback.jed' "DOTCLK AT14 PD0 PD1 PD2
 PD3 PD4 PD5 PD6 PD7 WSTRB UNK SEL0 SEL1 SBLU PBLU SGRN PGRN PRED SRED HS VS" output4 4 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\OUTPUT\output4.pld
~~~

SWITCH3

~~~
python.exe .\gal22v10parse.py '..\CG3\SWITCH\switch3_readback.jed' "XTAL VA4 VA3 VA2 VA1 VA0 BC6 BC5 PALSEL DOUBLE D512 P13 UP CUP DOTCLK HALFXTAL DDCLK VA8 CA4 VINC CDP DP" switch3 3 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\SWITCH\switch3.pld
~~~

SYNCGAL3

~~~
python.exe .\gal22v10parse.py '..\CG3\SYNCGAL\syncgal3_readback.jed' "V5 H3 H2 H1 H0 H4 H5 H6 V0 V2 V3 V4 LINC !LASTL !LRST V9 V8 L512 !HSYNC !VSYNC BLANK !VSCRST" syncgal3 3 "Chris Alfred" "Chris Alfred" "ESP-CG3" "Ux" > ..\CG3\SYNCGAL\syncgal3.pld
~~~
