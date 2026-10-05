# Slayer-Tesla-coil
A slayer Excited Tesla coil is a low power solid state tesla coil. A tesla coil is a high frequency transformer that is used to generate high voltages of electricity. It is self-oscillating and does not require precise tuning. A tesla coil was first created by Nikola Tesla in 1891, at the time it was a transformative step in his dream of acquiring wireless transmission of electricity, while we continue to use wire to transmit energy till date, it makes for an exciting project.
I was most inspired to make a Tesla coil by one of my fellow hack clubbers (whose name i cant remember), who made me realize that a tesla coil was quite achievable to make and design. i have been interested in it for a while and it was fun to do.
I built this by first understanding the physics behind a Tesla coil; electromagnetic induction. Then i made a schematic, i read more which led to consequential iterations of the schematic. I did the footprints assignments using Mouser Electronics and eventually updated my footprint library. i concluded by making the PCB(some of the parts are external tho) and viola!!
![](images/Screenshot(344).png)
![](images/Screenshot(347).png).

STEP 1
I did research on Tesla coils. Theres a lot of info about spark gap tesla coils but i decided to go with a slayer excited tesla coil instead utilizing either a feedback coil or a transistor. More details canbe found in the journal.md. Anyways after deciding on this. I read a bunch of instructions and watched YouTube videos and then made the schematic.

STEP 2
I got carried away although doing the footprints assignment but i do think it helped a lot in making the BOM and i made a PCB cause i thought it will be useful which it could be but my tesla coil is not using a PCB

step 3
I made the CAD which also helped me narrow down the specifications etcetra, get a better idea of what i am trying to do and gave me resources to use o calculate the resonant frequency which is important but not too much in a slayer excited tesla coil

step 4
I made the BOM, i looked through Ali Express for stuff, i decided on a battery which i hope i did well cause i dont want to use an adapter and voila. More details in Journal.md

The BOM
pandoc -f csv Sheet1.csv -o output.md
<img width="1920" height="1080" alt="Screenshot (360)" src="https://github.com/user-attachments/assets/06627da4-52c0-413a-8c3a-a9e718d011e8" />
https://docs.google.com/spreadsheets/d/1osx8s_dKkFnwftt5uLbFzMi76YqxEO74YxG5Nzp4THI/edit?usp=sharing

The Schematic
<img width="1920" height="1080" alt="Screenshot (361)" src="https://github.com/user-attachments/assets/b960f753-cce5-4996-b33c-3174aa5d9fca" />

The CAD
![](images/Screenshot(362).png)



| Reference | QTY | Component | Value | Notes | Estimated Prices | Link |
|---|---:|---|---|---|---:|---|
| Q2 | 1 | NPN Power Transistor | TIP31C | TO-220 Package | $1.10 per 10pcs | https://a.aliexpress.com/_EGoSctg |
| R2 | 1 | Resistor | 1kohms | Axial | Available | Available |
| C1 | 1 | Ceramic Capacitor | 100nF, 50V | Radial | $1.10 per 10pcs | https://a.aliexpress.com/_ExHqb2e |
| D2 | 1 | Diode | BAV16W | Fast switching | $0.86 for 20pcs | https://a.aliexpress.com/_EG9ENKm |
| L1 | 1 | Primary coil | 4 turns, 0.8mm magnet wire | Custom wound | $2.80 | https://a.aliexpress.com/_EzIT5KI |
| L2 | 1 | Secondary coil | 25 turns, 0.2mm magnet wire | Custom wound | $1.10 | https://a.aliexpress.com/_EIRpH5y |
| L3 | 1 | Feedback coil | 3 turns, 0.6mm magnet wire | Custom wound | $1.10 | https://a.aliexpress.com/_EIRpH5y |
| BT1 | 1 | Power supply | 9V Lithium ion battery | | $1.10 | https://a.aliexpress.com/_EwdnAp0 |
| 2 pin screw terminal | 2 | 2-pin screw terminal | 2-pin screw terminal | Power input | $1.23 | https://a.aliexpress.com/_Eze3ZSI |
| Perf Board | 1 | Perfboard | 7×9cm protoboard | Circuit Assembly | $1.10 | https://a.aliexpress.com/_EyrP0P4 |
| Solder iron | 1 | Solder Iron | USB or mains powered | Required tool | $6.96 | https://a.aliexpress.com/_EwgpuvC |
| PVC pipe | 1 | PVC pipe | 4 inches | Coil former | $1.10 for 2 pcs | https://a.aliexpress.com/_EzJuh94 |
| | | | | **Total** | **$19.55** | |


																									
																									

