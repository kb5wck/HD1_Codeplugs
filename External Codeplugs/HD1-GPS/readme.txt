Hinweistext
===========

Als erstes muss in der CPS die DMR ID eingetragen werden und zwar unter 
Basic Settings -> ID Settings -> in der ersten Zeile unter Radio ID die DMR ID eintragen (siebenstellig)

Ggf. muss über die CPS nun die User-Datenbank aktualisiert werden ...
Contacts -> Adress Book Contact -> "Import Contacts" (Auswahl von csv-Datei)
und dann mit "Write Contacts" ins Gerät übertragen

Es müssen nach dem Upload des Code Plugs die internen Parameter eingestellt werden und zwar über
Menü-Taste -> Main Set ->
dann z. B. 
Voice "off", Bestätigung mit "confirm"
CH-Mode "NAME", Bestätigung mit "confirm"

  
Hier nun eine Übersicht über die Einstellungen ...

Tastenbelegung
==============
SK1 kurz: wake up
SK1 lang: L/M/H Power
SK2 kurz: Radio
SK2 lang: 1750-Hz-Ton


Zonen
=====
DMR DB0FS
DMR DB0ZE
FM Rprt
DMR Simplex
FM Simplex


DB0FS/DB0ZE
===========
01	WW (91)
02	EU (92)
03	WWDE (910)
04	DACH (920)
05	DL (262)
06	TAC 1 (26200)
07 	TAC 2 (26299)
08	TAC 3 (26233)
09	TAC 4 (26266)
10	lokal (9)
11	Regio (8)
12	GrHH (26220)
13	NiNord (26236)
14	AfuNord (26225)
15	HH/SH (2622)
16	EMCOM EU (9112)

FM Rprt
=======
DB0FS			438,850/431,250 RX/TX: 88,5
DB0HHW		439.01250/431.41250
DB0HEW		438,550/430,950 RX-SQL: 91,5
DB0PI			438.66250/431.06250
DB0HHN		438.37500	430.77500	RX: 67,0
DB0XH-2		145.66250/145.06250 TX: 79,7
DB0XH-70	439.20000	431.60000 TX: 79,7
DF0HHH		438.70000/431.10000 TX: 67,0
DB0XJ			438.80000	431.20000 RX/TX: 67,0
DB0HT			439.12500/431.52500
DB0PR			439.35000	431.75000 TX:67,0
DB0NI 		438.77500/431.17500
DB0AGM		438.57500/430.97500


VHF Digital Simplex
===================
DV V17	145,2125
DV V18	145,2250
DV V19	145,2375
DV V20 	145,2500
DV V21	145,2625
DV V22	145,2750
DV V23	145,2875
DV V24	145,3000
DV V25	145,3125
DV V26	145,3250
DV V27	145,3373
DV V28	145,3500
DV V29	145,3625
DV Call	145,3750
DV V31	145,3875
DV V32	145,4000

VHF FM Simplex
===================
FM V18	145,2250
FM V20 	145,2500
FM V22	145,2750
FM V24	145,3000
FM V26	145,3250
FM V28	145,3500
FM V30	145,3750
FM V32	145,4000
FM V34	145,4250
FM V36	145,4500
FM V38	145,4750
FM Call	145,5000
FM V41	145,5125
FM V42	145,5250
FM V43	145,5375
FM V44	145,5500

UHF Digital Simplex
===================
DV U008	430,1000
DV U010	430,1250
DB U012	430,1500
DV U014	430,1750
DV U016	430,2000 
DV U018	430,2250
DV U020	430,2500
DV U022	430,2750
DV Call	433,4500
DV U289	433,6125
DV U290	433,6250
DV U291	433,6375
DV U292	433,6500
DV U293	433,6625
DV U294	433,6750
DV U295	433,6875

UHF FM Simplex
===================
FM U244	433,0500
FM U246	433,0750
FM U248	433,1000
FM U250	433,1250
FM U252	433,1500
FM U254	433,1750
FM U256	433,2000
FM U258	433,2250
FM U260	433,2500
FM U262	433,2750
FM U264	433,3000
FM U266	433,3250
FM Call	433,5000
FM U282	433,5250
FM U284	433,5500
FM U286	433,5750
