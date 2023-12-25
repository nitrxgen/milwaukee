# Milwaukee Tools Model Numbers Explained
#### Formatting

`[system] [ONE][series][base][options]-[accessories]`

#### Battery Technologies
| Technology | Meaning |
| - | - |
| L4 | 
| M12 | Milwaukee, 12 Volt |
| M18 | Milwaukee, 18 Volt |
| MXF | Milwaukee Fuel |

| Base Model | Meaning |
| - | - |
| AG | Angle Grinder
| BDD | Brushless Drill Driver |
| BPD | Brushless Percussion Drill |
| CCS | Circular Saw |
| CD | Compact Driver |
| CDD | Compact Drill Driver |
| CID | Compact Impact Driver |
| CIW | Compact Impact Wrench |
| CLL | Cross Line Laser |
| COS | Cut-Off Saw |
| COSC | Cut-Off Saw Cart |
| CPD | Compact Percussion Drill |
| CSZ| Sawzall |
| CVBP | Concrete Vibrator Backpack |
| FDGA | Fuel Range, 
| FHPX | Fuel Hammer Percussion with FixTec
| FHIWF | Fuel High torque Impact Wrench w/ Friction ring
| H | Hammerdrill |
| CHIWF | Fuel High torque Impact Wrench w/ Friction ring
| CHIWP | Fuel High torque Impact Wrench w/ Pin detent

#### Cordless Angle Grinders
``` /^(ONE)?[CF]H?L?S?AG[FV]?(115|125|230)XP?D?B?/ ```

F  AG  125 X PDB
F SAG  115 X PDB - paddle
F SAGV 115 X PDB - 5step dial
F SAGF 125 X PDB - flat gear head
F SAGV 125 X B
FL AG  230 X PDB - paddle, brake, fixtec, antikickback, linelockout
BLSAG  115 X PD - brushless

FHSAG  (125|125) X PDB - high output, linelockout, no antikickback, fixtec, brake
  SAG  115 X PDB - 
C  AG  115 X PD - Cordless (C), Angle Grinder (AG), Paddle (P)
C  AG  125 X PDB
C  AG  125 X - no paddle, powerstate, 

F = Fuel
C = Cordless
 H = High Output
 L = Large? over 180mm
 S ???
   AG = Angle Grinder
     F = Flat Gear Head
     V = Variable Speed
      123 = disc size
         X = FixTec
           P = Paddle (slide switch if omitted)
            D = 
             B = Braking


_ HS XP
Fuel (F), Angle Grinder, 125 mm (125), FixTec (X), Rapidstop Disc Brake (DB)

#### Corded Angle Grinders

``` ^AGV?M? \d{1,3}\-\d{3} G?E?X?(\/DMS)? ```
AG = Angle Grinder
V = Antivibrate System Motor Housing, this is unrelated to Autobalancer System
+M = Milwaukee B-Guard protects from kickback effect
-M = softstart for smooth startup

INOX? low speed grinder variable speed, 
XPD = paddle, 

G = Rotatable Main Handle
/
DMS = Dead Man Switch
-DMS = no line lockout function

   AGV 13 115 XSPDE = corded, paddle, 1250W, Soft Start, Line LockOut, 
   AGV 15-125 CX AVS- 1550W, AVS? antivoltagesurge, antikickback, corded?
   AG 10-125 EK = 1000 W
   AG 16-125 XC = 1520W
   AG 16-125 XC/DMS = 1520 W
   AG 800-115 E = 800W
   AGV 22-230 DMS - 2200

| Number | Wattage |
| - | - |
| 8 | 750 W |
| 800 | 800 W |
| 9 | 850 W |
| 10 | 1000 W |
| 12 | 1200 W |
| 13 | 1250 W |
| 14 | 1450 W |
| 15 | 1500 W, or 1550 W |
| 16 | 1520 W |
| 17 | 1750 W |
| 21 | 2100 W |
| 22 | 2200 W |
| 24 | 2400 W |
| 26 | 2600 W |

Sizes are only ever 115, 125, 180, or 230 mm.

#### Accessories

M4 B2
M12 B2, B3, B4, B5, B6
M18 B2, BX (3Ah)m B4, B5, B6, B9
M28 BX (3Ah), B5

| Code | Meaning | L4 | M12 | M18 | MXF | Total Capacity | Charger
| - | - | :- | :- | :- | :- | :- | :- |
| 0 | No accessories | | | | | | |
| 21 | | | 1 &times; 1.5 Ah | | | 1.5 Ah | 30 min |
| 22 | | | 2 &times; 1.5 Ah | | | 3.0 Ah | 30 min |
| 32 | | | 2 &times; 3.0 Ah | | | 6.0 Ah | 60 min |
| 121 | | | | 1 &times; HB12 | | 12.0 Ah | FC |
| 122 | | | | 2 &times; HB12 | | 24.0 Ah | FC |
| 151 | | | 1 &times; 1.5 Ah | | | 1.5 Ah | 30 min |
| 201 | | | 1 &times; B2 | 1 &times; B2 | | 2.0 Ah | C/FC |
| 202 | | | 2 &times; B2 | 2 &times; B2 | | 4.0 Ah | C/FC |
| 301 | | 1 &times; B3 | 1 &times; B3 | | 1 &times; CP203 | 3.0 Ah | C/L4 |
| 302 | | | | 2 &times; HB3 | | 6.0 Ah | C/FC |
| 401 | | | 1 &times; B4 | | | 4.0 Ah | C |
| 402 | | | 2 &times; B4 | 2 &times; B4 | | 8.0 Ah | C/FC |
| 421 | | | 1 &times; B2, 1 &times; B4 | 1 &times; B2, 1 &times; B4 | | 6.0 Ah | C |
| 422 | | | 1 &times; B2, 1 &times; B4 | | | 6.0 Ah | C |
| 501 | | | | 1 &times; B5 | | 5.0 Ah | C/FC |
| 502 | | | | 2 &times; B5 | | 10.0 Ah | C/FC |
| 551 | | | | 1 &times; HB5.5 | | 5.5 Ah | FC |
| 552 | | | | 2 &times; HB5.5 | | 11.0 Ah | FC |
| 602 | | | 2 &times; B6 | | 2 &times; XC406 | 12.0 Ah | C/Integrated |
| 622 | | | 1 &times; B2, 1 &times; B6 | | | 8.0 Ah | C |
| 802 | | | 1 &times; B2, 1 &times; B6 | 2 &times; HB8 | | 16.0 Ah | FC |

##### Observations:
- The first digit indicates the highest single battery pack capacity.
- The second digit indicates either the second digit to the capacity, or that you get two different capacity battery packs.
- The last digit is usually 1 or 2 indicating how many batteries in total come with it.
- The only misnomer seems to be 421 where 2 different capacity packs are included but the last digit is 1 for reasons unknown.

##### Notes:
- L4 batteries use USB to charge and come with a USB cable.
- M12 C chargers only work with M12 batteries.
- M18 C chargers with with both M12 and M18 batteries.
- MXF C chargers only with with MXF batteries.


| Code | Meaning |
| - | - |
| B | Carry tool bag |
| C | Kitbox |
| P | PackOut Case |
| X | HD Case |
