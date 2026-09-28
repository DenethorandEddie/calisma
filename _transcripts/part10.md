# Part 10 Transcripts

## IMG_0991

**Document:** Fuel efficiency / ground operation table (likely a SunExpress fuel policy or fuel-saving guidance section, comparing 737-800W and 737-8 MAX). The document name and page are not visible.

| GROUND OPERATION | 737-800W | 737-8 |
|---|---|---|
| **APU**<br>Fuel can be saved by minimizing APU utilization. Average fuel flow for normal APU operation on the ground: | 105 kg/hr | 107 kg/hr |
| **TAXIING** | 12 kg/min | 10.5 kg/min |

Sometimes it is not an opportune moment to use EOT because of weather and taxi way conditions. The airports may not allow this either because of bad taxi ways. If it is allowed and the conditions are good the pilot may use this method if he or she thinks it is appropriate.

Sample Procedure: [cut off; only the top of this heading is visible at the bottom edge]

(EOT = Engine Out Taxi, i.e. single-engine taxi.)

---

## IMG_1014

**App screenshot:** OPT / EFB performance calculator, "PERFORMANCE - TAKEOFF", showing the **Rwy Graphic** view (toggle ON). Status bar: 21:16, 28 Eyl Pzt [28 Sep, Mon], battery 88%.

**Header / buttons:** PROFILE **TC-SOH** | ARPT Info | Add Airport | NOTAM | MEL | CDL | Send Output | Nav Plates

**Inputs (left column):**
| Field | Value | Sub-value |
|---|---|---|
| ARPT | EHAM / AMS | |
| RWY | 18L | |
| INTX | FULL 18L | |
| COND | 4 - GOOD TO MEDIUM | |
| WIND | 0 KT | 0 HW/0 XW KT |
| OAT | -4 C | 25 F |
| QNH | 1025.0 HPa | 30.27 IN HG |

**Inputs (middle column):**
| Field | Value |
|---|---|
| THRST | OPTIMUM |
| TASS | MAX (greyed) |
| FLAP | OPTIMUM |
| E BLD | ON |
| A/I | ENGINE |
| V1/VR | OPTIMUM |

**Inputs (right):** TOW: **69500 KG** · CG(%): **28**

**Engine Failure Procedure:** EOSID: At 25 NM [AMSX4 (N5154.4 E00444.5)] enter HLDG (181 INBD,RT)

**Aircraft/engine:** 737-800/CFM56-7B26 · mode selector **FULL** (selected) / ATM · Rwy Graphic: ON

**Outputs (runway graphic):**
| Item | Value | | Item | Value | | Item | Value |
|---|---|---|---|---|---|---|---|
| AE-GO (green) | 2128 M | | TORA | 3400 M | | SLOPE | 0.01% |
| EO-GO (magenta) | 2226 M | | TODA | 3460 M | | WEIGHT | 69500 KG |
| ACCEL-STOP (blue) | 2241 M | | ASDA | 3400 M | | | |

- Large watermark: **FULL**
- **XW LIMIT: 20 KT**; wind rose shows 0 XW, 0 HW
- Runway bar graphic for 18L: intersection markers **E5, E4, E8, E2** along the top; bars for AE-GO, EO-GO and ACCEL-STOP ending at about 62–65% of the length; end markers TORA, TODA, ASDA.

**Bottom tabs:** TKO Dispatch (selected) | TKO All Engine | LDG Dispatch | LDG Enroute

---

## IMG_1015

**App screenshot:** the same "PERFORMANCE - TAKEOFF" page as IMG_1014, with the same inputs, but with **Rwy Graphic OFF**, so the numeric takeoff results are shown. Status bar: 21:16, 28 Eyl Pzt, battery 87%.

**Inputs (identical to IMG_1014):** PROFILE TC-SOH; ARPT EHAM / AMS; RWY 18L; INTX FULL 18L; COND 4 - GOOD TO MEDIUM; WIND 0 KT (0 HW/0 XW KT); OAT -4 C (25 F); QNH 1025.0 HPa (30.27 IN HG); THRST OPTIMUM; TASS MAX (greyed); FLAP OPTIMUM; E BLD ON; A/I ENGINE; V1/VR OPTIMUM; TOW 69500 KG; CG(%) 28.

**Engine Failure Procedure:** EOSID: At 25 NM [AMSX4 (N5154.4 E00444.5)] enter HLDG (181 INBD,RT)

**Aircraft/engine:** 737-800/CFM56-7B26 · FULL (selected) / ATM · Rwy Graphic: OFF

**Outputs:**
| Item | Value |
|---|---|
| FLAP | 5 |
| EO ACCEL HT | 1610 ft AGL |
| TRIM | 5.00 |
| RWY / INTX | 18L |
| TOGW | 69500 KG |
| TO-2 | 88.2 (N1 %) |
| Thrust (watermark) | FULL |
| V1 | 132 KT |
| VR | 143 KT |
| V2 | 148 KT |
| Vref40 | 142 KT |

Note: with engine anti-ice ON at -4 C, the tool selected FULL thrust with the TO-2 rating (derate 2). N1 is 88.2. No assumed-temperature reduction is applied.

**Bottom tabs:** TKO Dispatch (selected) | TKO All Engine | LDG Dispatch | LDG Enroute

---

## IMG_1016

**App screenshot:** Jeppesen FliteDeck-style EFB. The chart is the EHAM Airport Moving Map (AMM), zoomed on the northern end of RWY 18L. Header: "EHAM-AMM: 3 Sep - 30 Sep"; v 7.3.0.8021; aircraft 737-8/-800. Status bar: 21:17, 28 Eyl Pzt, battery 87%.

**Left panel:** EHAM, Amsterdam - AMS · APT Info · tabs Clipboard (selected) / All Charts
Clipboard list:
| Chart | Date |
|---|---|
| AOI | 20 AUG 2026 - 01 OCT 2026 |
| AMM | 3 SEP - 30 SEP (selected) |
| [18L] RENDI 3E RNAV | 19 MAR 2026 |

**Map content:**
- Runway **18L/36R** runs vertically. The **18L** threshold marker is at the top and the **36R** marker is at the bottom. Windsock symbols are shown near both ends.
- Runway **27** (label on the right) crosses 18L/36R horizontally (runway 09/27).
- Taxiway **E6** runs from the 18L threshold (top), curves west and then south, and joins **N2** at the crossing with runway 09/27.
- Taxiway **N2** (labelled three times) runs south-west toward the apron.
- Taxiway **E5** runs horizontally near the bottom and meets 18L/36R. Blue intersection label: **E5 2820 m / 9252 ft** (takeoff run available from intersection E5 on 18L).
- Taxiway **E7** runs from E5 to the south-east.
- Other labels: **A13**, **PD**, **P-HOLDING**, **P2**, **B**. A red no-entry symbol is shown at the west end of the E5 taxiway line.
- Yellow and red stop-bar/holding-position markings appear along the taxiways.

**Bottom bar:** ← AOI | RENDI 3E RNAV →

---

## IMG_1017

**Document:** Jeppesen-style Airport Operational Information (AOI) for EHAM - AMS, **page 17 of 25** ("AOI 17/25"). Note on screen: "Chart not georeferenced."

### 3 DEPARTURE
#### 3.1 Take-off Minima

| RWY | | 06, 27, 18C/36C | |
|---|---|---|---|
| All ACFT | ft - m/km | 0 - 75R | - |

| RWY | | 09, 24, 18L, 36L | |
|---|---|---|---|
| All ACFT | ft - m/km | 0 - 125R | - |

| RWY | | 22 | |
|---|---|---|---|
| All ACFT | ft - m/km | 0 - 400R/400V | - |

| RWY | | 04 | |
|---|---|---|---|
| All ACFT | ft - m/km | 0 - 400V | - |

| RWY | | 18R, 36R | |
|---|---|---|---|
| All ACFT | ft - m/km | Not authorized | - |

#### 3.2 Speed
MAX IAS 250KT below FL100 unless otherwise instructed. In case ATC allows/instructs to accelerate beyond IAS 250KT for operational purposes, the speed limitations on early SID turns (MAX IAS 220KT) remain applicable and shall be respected.

#### 3.3 Communication
On initial contact with DEP report: Call-sign, actual ALT, SID, mention additional instructions from TWR. If cleared on a HDG for initial DEP, the HDG shall be used instead of SID.

When changing channel from Schiphol Departure to Amsterdam ACC, initial contact shall consist of Amsterdam Radar and callsign only. When a speed or heading has been assigned, this information shall be included in the initial contact.

In case of short taxi times and due limited HLDG space at RWY, pilots are requested to inform GND before transfer to TWR if not yet ready for DEP and expect extended taxi routing (dynamic delays).

#### 3.4 Communication Failure
If possible call Amsterdam ACC Supervisor on TEL number +31 (0)20 406 3999.
- Note: Use TEL connection to mitigate COM failure only. All TEL calls will be automatically recorded.

If TEL connection is disconnected prematurely (before read-back), revert to general communication failure procedure.

Follow SID or departure instructions at TKOF for route and altitude limits until the last waypoint, unless cleared to climb or rerouted.

#### 3.5 Start-up Procedures
##### 3.5.1 Start-up/Push-back
A request for start-up shall be made after all preparations for DEP have been made, if necessary push-back truck connected. [continues on page 18, see IMG_1018]

---

## IMG_1018

**Document:** EHAM - AMS AOI, **page 18 of 25** ("AOI 18/25"). Note on screen: "Chart not georeferenced." The top line is cut off; it is the end of 3.4 ("...waypoint, unless cleared to climb or rerouted."). This page overlaps with the end of IMG_1017.

#### 3.5 Start-up Procedures
##### 3.5.1 Start-up/Push-back
A request for start-up shall be made after all preparations for DEP have been made, if necessary push-back truck connected.

Cross-bleed start prohibited at the ACFT stand.

Flight crew shall read back to ATC all instructions contained in the push-back CLR and ensure that the complete push-back CLR from ATC is communicated word-for-word to the push-back crew.

##### 3.5.2 ATC Slot and Clearance
REQ ENRT CLR via DCL, except flights:
- planned below FL60;
- with no SID;
- cleared for RWY 24 DEP and unable to fly cleared SID utilising RF turns;
- unable to receive DCL CLR.

ENRT CLR shall be REQ at Schiphol DLV MAX 20min prior to EOBT or 35min prior to CTOT. If RWY 36L in use, REQ CLR MAX 30min prior to EOBT or 45min prior to CTOT.

After having obtained ENRT CLR, switch immediately, without ATC instructions, to Schiphol Planner.

REQ start-up when actually ready (doors CLSD, CLR received, push-back truck connected, etc).

Contact GND when instructed for start-up, push-back (if applicable) and taxi instructions.

ACFT shall move within 1min after having obtained start-up and push-back CLR, otherwise the CLR expires and shall be requested again.

If not able to comply with the crossing conditions prescribed in the SIDs, inform DLV as soon as possible.

##### 3.5.3 Airport Collaborative Decision Making (A-CDM)
CDM concept in use at this airport. See General Part/RAR/RAR In-Flight and in addition:

The pilot shall report ready on the Schiphol Planner channel when:
- all handling processes are finished (doors CLSD, handling equipment removed), if required the push-back truck connected, the ACFT lifted, the pilot ready for immediate push-back.
- within TSAT window (TSAT -/+5min)

The report shall include:
- ACFT identification
- position
- ATIS information
- report ready

The GND handler sets an accurate TOBT. If an earlier DEP is anticipated, or the TOBT can no longer be met, contact the GND handler as soon as possible to update the TOBT. TOBT adherence will be monitored and reported to AO/GND handler.

TSAT is displayed on most contact stands via VDGS or should be requested from GND [cut off]

---
## IMG_1020

**Document:** EHAM - AMS AOI, **page 19 of 25** ("AOI 19/25"). Note on screen: "Chart not georeferenced."

(End of 3.5.3, continued from IMG_1018:) When using DCL maintain a listening watch on CLR delivery channel.

#### 3.6 Departure Procedure
##### 3.6.1 Requirements for Operators
**Application of RNAV**
All SIDs require the use of RNAV routes stored in a pre-programmed navigation database on board of ACFT. Furthermore:
- Connect FMS as early as possible.
- Turn anticipation is mandatory for all WPTs except those which are underlined, these WPTs shall be overflown.
- The navigation aid (e.g. VOR) mentioned in the column "Expected path terminator" is for selection of MAG station declination only.

##### 3.6.2 Minimum Runway Occupancy Time (MROT)
Ensure standard MROT procedures. Refer to RAR and in addition:

On receipt of line-up CLR, pilots should ensure that they are able to comply with given instructions immediately.

On receipt of TKOF CLR pilots should ensure that they are able to commence TKOF without delay.

When unable to comply with the above, inform ATC as soon as possible once transferred to TWR. The TKOF CLR may be revoked.

DEPs RWYs 24, 27, 36C execute TKOF immediately after receiving the CLR due to converging APCH and DEP PROCs.

##### 3.6.3 Intersection Take-off
All JET ACFT must use full RWY length AVBL for noise abatement reasons.

ATC may assign intersection TKOF to any ACFT for operational reasons.

FLTs from APN S departing from RWY 24 will be assigned INT TKOF TWY S8.

##### 3.6.4 Remote Hold
**Remote Holding Positions**

Remote holding PROCs may be used by ATC in the following cases:
- The designated stand is occupied by another ACFT.
- DEP ACFT must vacate the gate for arriving ACFT, but are not yet allowed to depart due to the assigned CTOT by the Network Manager.

All TFC must be able to leave the remote HLDG without delay. Unless otherwise instructed by ATC all TFC must enter and leave the remote HLDG via the standard taxi route. DEP ACFT will be towed to remote HLDG position.

The following APN PSNs are AVBL for remote holding:

| Apron | Location | Positions | MAX Wingspan | Remarks |
|---|---|---|---|---|
| P-holding | Between TWY A12 and A13 | P1 | 69m / 226ft | Either P1 AVBL or PA and PB AVBL. Either P3 AVBL or PC and PD AVBL. |
| | | P2 | 36m / 118ft | |
| | | P3 | Not applicable | |
| | | PA, PB, PC, PD | 36m / 118ft | |
| On R-APRON | Adjacent to TWY R | P20 | 36m / 118ft | Enter via TWY R. CL and designated [cut off] |

(The table is cut off here and continues on page 20; see IMG_1021.)

---

## IMG_1021

**Document:** EHAM - AMS AOI, **page 20 of 25** ("AOI 20/25"). Note on screen: "Chart not georeferenced." The first rows repeat the end of IMG_1020.

**Remote holding positions table (complete):**
| Apron | Location | Positions | MAX Wingspan | Remarks |
|---|---|---|---|---|
| P-holding | Between TWY A12 and A13 | P1 | 69m / 226ft | Either P1 AVBL or PA and PB AVBL. Either P3 AVBL or PC and PD AVBL. |
| | | P2 | 36m / 118ft | |
| | | P3 | Not applicable | |
| | | PA, PB, PC, PD | 36m / 118ft | |
| On R-APRON | Adjacent to TWY R | P20 | 36m / 118ft | Enter via TWY R. CL and designated stop PSN not lighted. (P20 and P21) |
| | | P21 | 36m / 118ft | |
| | Adjacent to TWY Q and TWY R | P22 | 36m / 118ft | Enter via TWY A or TWY Q and P23. CL and designated stop PSN not lighted. |
| | | P23 | 36m / 118ft | Enter via TWY A or TWY Q. Exit via P22. CL and designated stop PSN not lighted. |
| On TWY VS | East of holding RWY 36L | P6 | Not applicable | Either P6 AVBL or P6A and P6B AVBL. |
| | | P6A, P6B | 36m / 118ft | |
| | | P7 | Not applicable | Either P7 AVBL or P7A and P7B AVBL. |
| | | P7A, P7B | 36m / 118ft | |

At the end of the combined lead-in line of remote HLDG PSN P20 and P21 pilots shall turn 180° left for P20, or 180° right for P21 to hold nose out at the designated stop PSN.

**Towing to a remote holding position (outbound ACFT)**

Push-back and towing:
- Flight crew follows truck driver's instruction and does not contact GND.
- Transponder and engines remain switched off.
- Anti-collision lights switched on.

On remote holding position:
- Anti-collision lights remain switched on.
- Flight crew activates the transponder with the transponder code received from DLV.
- Flight crew contacts Planner and confirms positioned at the remote HLDG position.
- Planner will confirm transponder on radar and will instruct flight crew to monitor GND (monitor Planner on the second communication set for possible reclearances).
- Flight crew instructs the truck driver to disconnect and awaits the "ALL CLEAR" signal from GND crew.
- ENG remain switched off; no prior approval required to use the APU.
- No GPU AVBL at the remote HLDG position.

Taxi out:
- Flight crew contacts GND in TSAT window for start-up and taxi instruction.
- Flight crew receives ATC instruction to taxi-out.

---

## IMG_1022

**Document:** EHAM - AMS AOI, **page 21 of 25** ("AOI 21/25"). Note on screen: "Chart not georeferenced." The top overlaps with the end of IMG_1021 ("No GPU AVBL at the remote HLDG position."; "Taxi out" items).

Taxi out:
- Flight crew contacts GND in TSAT window for start-up and taxi instruction.
- Flight crew receives ATC instruction to taxi-out.

**Push-back and towing to another stand (outbound ACFT)**
- Flight crew follows truck driver's instruction and does not contact GND.
- Transponder and ENG remain switched off.
- Anti-collision lights switched on.

On stand:
- Anti-collision lights switched off, to be switched on just prior to push-back.
- Tow truck remains connected.
- Flight crew contacts Planner and confirms positioned at the new stand.
- ENG remain switched off; no prior approval required to use the APU.
- Flight crew contacts Planner in TSAT window.
- No GPU AVBL.

**Towing to aircraft stand G71 (outbound aircraft)**

Push-back:
- ACFT is pushed onto stand G71, positioned nose-out.
- Transponder and ENG remain switched off.

On stand:
- Flight crew holds brakes; no chocks required.
- Anti-collision lights remain switched on to ensure GND crew stays clear of the stand.
- Flight crew receives "ALL CLEAR" signal from GND crew.
- ENG remain switched off; no prior approval required to use the APU.

Taxi out:
- ENG start-up on stand only after start-up approval from ATC.
- Cross-bleed start is prohibited.
- Flight crew receives ATC instruction to taxi-out.

##### 3.6.5 Wake Turbulence Recategorization (RECAT)
RECAT-EU standards applied. See RSI EUR and in addition:

Minimum addition of 80sec for a lower heavy (CAT C) behind an upper heavy (CAT B) is required for safety reasons. Additional 60sec will be applied when DEP from an intermediate part of the same RWY.

Inform ATC if greater wake turbulence separation is required, upon receiving line-up CLR.

##### 3.6.6 Flight Planning Departure
Flights DEST EHRD and EHLE are exempted from flying SIDs within EHAM TMA.

**RWY 04 SIDs:**
- LOPIK 2F
  For TFC with DEST EHBK via T605 and for TFC with DEST EHBD and EHEH.
  For TFC via CDR N852.

**RWY 06 SIDs:** [cut off]

---

## IMG_1029

**Chart:** Jeppesen-style EFB chart, **"AGC Overview" – EHAM - AMS** (Aerodrome Ground Chart overview for Amsterdam Schiphol). Note on screen: "Chart not georeferenced." Bottom navigation: ← AGC East | Tempo AGC SUP 30/... →. Status bar: 21:19, 28 Eyl Pzt, battery 87%.

**Description:** Diagram of the whole airport. It is split into two dashed-outline regions, **AGC West** (runway 18R/36L, the Polderbaan) and **AGC East** (the main runway complex). The top border shows longitudes E004°40', E004°45', E004°50'. The left border shows latitudes N52°21' and N52°19'.

**Frequency box (top right):**
| Service | Freq | Use | Freq | Use |
|---|---|---|---|---|
| D-ATIS | 132.980 | ARR | 122.205 | DEP |
| Schiphol TWR | 119.230 | RWYs 04/22, 18L/36R | 118.105 | RWY 18C/36C |
| | 118.280 | RWY 18R/36L | 135.110 | RWY 06/24 |
| Schiphol GND | 121.705 | RWY 06/24 | 121.560 | RWY 18R/36L |
| | 121.805 | RWYs 04/22, 09/27, 18L/36R | | |
| | 121.590 | by ATC (ALTN for DLV and Planner) | | |
| | 121.905 | RWY 18C/36C | | |
| Schiphol Planner | 121.655 | Outbound Planner | | |
| APN | 121.880 | J - Apron | 121.930 | K - Apron |
| Schiphol DLV | 121.980 | | 131.355 | Operational Info |
| DCL | – | | | |
| Schiphol AOM | 130.480 | Airside OPS Manager | | |
| Padcontrol | 121.605 | | | |
| Snowdesk | 121.305 | De-Icing | | |

**Runways (circle label: magnetic heading, elevation):**
| RWY end | MAG HDG | Elev (ft) | Dimensions |
|---|---|---|---|
| 18R | 181° | -13 | 3800 x 60 (18R/36L) |
| 36L | 001° | -12 | |
| 18C | 181° | -12 | 3300 x 45 (18C/36C) |
| 36C | 001° | -12 | |
| 18L | 181° | -12 | 3400 x 45 (18L/36R) |
| 36R | 001° | -11 | |
| 09 | 084° | -12 | 3453 G 45 (09/27) |
| 27 | 264° | -12 | |
| 06 | 055° | -11 | 3439 G 45 (06/24) |
| 24 | 235° | -12 | |
| 04 | 039° | -13 | 2020 G 45 (04/22) |
| 22 | 219° | -14 | |

**AGC West labels:** 18R "Turn around area available"; taxiways V1, V2, V3, V4, V; FIRE STATION; TWR West 183; AMSTERDAM VOR/DME **113.95 AMS**; CAUTION: "Do not mistake highway for runway." (Highway labels run along the west side of 18C/36C.)

**AGC East labels:**
- SCHIPHOL **D 108.4 SPL** (DME)
- Remark: Hotspots: see APC Hotspots
- Taxiways W1–W13 (W1, W2, W3, W4, W5, W6, W7, W8, W9, W10, W11, W12, W13), Y, C, D, Z, B, A
- U APRON; "See APC APN J, U, Y" (shown twice); J APRON; De-Icing; HS (hotspot) boxes; Y
- 09: "See APC Main Terminal"; FIRE STATION
- N5, N4, N3, N9, N2, N1; G-pier, H-pier, F-pier, E-pier; E; D; TWR Center 320; TERMINAL; B-pier / C-pier
- ARP N 52 18.5 E 004 45.9
- CARGO (several); A APRON; R APRON; S APRON; II & III; WIP; S1, S2, S3, S4, S5I, S6, S7, S8, S9, S10; VIII; "See APC APN A/R"; "See APC APN S"; FIRE STATION (near S8)
- E1, E2, E3, E4, E5, E6, E7, E8, E9, E10; N; G, G1, G2, G3, G4, G5, G6, G7, G8; M; H
- "Engine run up area" (near 27 / N1); GA TERMINAL; K APRON; HANGARS (two); "See APC APN K/M"
- 06: "Turn around area available"
- Scale: m 0 / 500 / 1000; ft 0 / 1000 / 2000 / 3000
- Bottom-left: VAR 2° E, MAG UP; AD ELEV -11

---

## IMG_1030

**Chart:** Jeppesen-style EFB chart, **"APC Main Terminal" – EHAM - AMS** (Apron Chart). Note on screen: "Chart not georeferenced." Bottom navigation: ← APC Apron S | Stand Coordinates →. Status bar: 21:19, 28 Eyl Pzt, battery 86%.

**Description:** Detailed apron chart of the main terminal area between the 18C/36C side (west) and runway **36R/18L** (east). It shows taxiways, piers, stand numbers, ATC service boundaries (dashed purple lines) and standard taxi flow arrows. Runway **24** is at the bottom right. "Not to scale."

**Frequency box (bottom left):** same as in IMG_1029: D-ATIS 132.980 ARR / 122.205 DEP; Schiphol TWR 119.230 RWYs 04/22, 18L/36R, 118.105 RWY 18C/36C, 118.280 RWY 18R/36L, 135.110 RWY 06/24; Schiphol GND 121.705 RWY 06/24, 121.560 RWY 18R/36L, 121.805 RWYs 04/22, 09/27, 18L/36R, 121.590 by ATC (ALTN for DLV and Planner), 121.905 RWY 18C/36C; Schiphol Planner 121.655 Outbound Planner; APN 121.880 J - Apron, 121.930 K - Apron; Schiphol DLV 121.980, 131.355 Operational Info; DCL; Schiphol AOM 130.480 Airside OPS Manager; Padcontrol 121.605; Snowdesk 121.305 De-Icing.

**Taxiway / area labels:**
- Northern taxiways: B (outer), A (inner), N4 (x2), N3 (marked ③), N9, N2 (x2), E5, E7
- Connectors: A19C, A19W, A19E, A18, A17, A16, A15, A14, A13, A12, A11, A10, A9, A9C, A8, A7, A6, A5, A4, A3
- East side: P HOLD with remote holding positions PD, P3, PC, P2, PB, P1, PA (drawn twice for the alternative layouts); E8, E9, E4, E3, E2, E1, E10; N; L; H; S7, S7W (marked ②), S7E, S6, S5, S8
- G APRON with lead-in centre lines coloured **Blue / Yellow / Orange**; H APRON; HN
- G-PIER stands: G79, G76, G73, G71, G9, G8, G7, G6, G5, G4, G3, G2
- H-PIER stands: H1, H2, H3, H4, H5, H6, H7
- F-PIER stands: F3, F4, F5, F6, F7, F8, F9
- E-PIER stands: E3, E4, E5, E6, E7, E8, E9, E17, E18, E19, E20, E22, E24
- E APRON stands: E72, E75, E77; D APRON: D88, D90, D92, D93, D94, D95
- D-PIER stands: D2, D3, D4, D5, D7, D10, D12, D14, D16, D18, D22, D24, D26, D28, D23, D25, D27, D29, D31, D41, D43, D44, D47, D48, D49, D51, D52, D53, D54, D55, D56, D57; EXTENSION 1; EXTENSION 2
- C-PIER stands: C5, C6, C7, C8, C9, C10, C11, C12, C13, C14, C15, C16, C18
- B-PIER stands: B15, B17, B23, B27, B31, B35; A4E, A4W
- TERMINAL; ARP N 52 18.5 E 004 45.9; TWR Center 320; CARGO I; WIP; "see APC APN A/R/S"
- Bottom-left: VAR 2° E, MAG UP; AD ELEV -11; Not to scale

**Notes:**
- ① CAUTION: Avoid HLDG on the upslope BTW A19 and A20 to prevent backward movement of the ACFT.
- Remarks: Hotspots: see APC Hotspots
- Caution:
  - ② TWY S7W shall only be used for crossing RWY 06/24.
  - ③ When vacating RWY 27 N3 for TWY A take the first left turn on N3 to enter TWY A14, then turn left onto TWY A.
  - ④ Displaced RWY 36R end is indicated by red lights across the RWY. Do not cross displaced RWY 36R end.
- CAUTION: Do not mistake E1 (RWY 36R) for S7 (RWY 24)!
- Legend:
  - dashed purple line = ATC Service Boundary
  - Blue = TWY center line colour
  - arrow = Standard taxi routing, unless otherwise instructed by ATC. All other routes may be used two-way at ATC discretion only.
  - turn symbol = Turn prohibited for wingspan > 36m/ 118ft

---

## IMG_1031

**Document:** EFB "Chart NOTAM" – EHAM - AMS (Airport Chart NOTAM Bulletin), page 1 of the scroll. Status bar: 21:20, 28 Eyl Pzt, battery 86%.

**Left panel:** EHAM Amsterdam - AMS; APT Info; Clipboard / All Charts (selected); runway buttons 04, 06, 09, 18C, **18L (selected)**, 18R, 22, 24, 27, 36C, 36L, 36R; ☑ Effective Charts Only; Hide Filters; NOTAMs (expanded) > Chart NOTAM; General; Ground Charts; SID; STAR.

**Content:**

Airport Chart NOTAM Bulletin
# EHAM Amsterdam / Schiphol

**Airport**
- AGC, APC Apron A/R Tempo charts
  ```
  Check tempo charts distributed for this AD:
  Tempo AGC SUP 30/25 Phase 26.0, 26.1, 26.2
  ```
- AOI TWY Restrictions
  ```
  Amend
  Oversteering is required for A346, A351, A380, B773 and larger.

  to read:
  Oversteering is required for A346, A35K, A380, B773 and larger.
  ```

**Navaids**
- NIL

**Runway**
- NIL

**SID**
- SID, SIDPT RNAV SIDs RWY 04
  ```
  REF AIP SUP 11/26

  ANDIK 3F, BERGI 2F, VOLLA 2F changed due to crane.
  No turns allowed before 600 FT.
  Crane 275ft AMSL, 3540m / 11614ft beyond RWY 04 TORA and
  690m / 2264ft left of EXTD RCL.

  Any changes will be promulgated by NOTAM.
  ```
- SID, SIDPT RNAV SID RWY 09
  ```
  REF AIP SUP 30/2026
  FM 17 SEP 2026 to UFN
  VALKO 5M MNM climb gradient of 3.6% due to crane.
  Crane N52 18.3 E004 52.0, 299ft AMSL, 311ft AGL
  ```

**STAR**
- NIL

**Procedures**
- NIL

**Minima**
- IAC/ AFC Minima RNP 04
  ```
  TEMPO minima REF SUP 14/26:
  MON-SAT 0500-1900 (-1)

  RNP LPV CAT 1 04
  Cat B: C 900ft, DA 280ft, V 3.6km
  Cat C: C 900ft, DA 290ft, V 3.6km
  Cat D: C 900ft, DA 300ft, V 3.6km
  ```
- IAC/ AFC Minima ILS or LOC 27
  ```
  TEMPO Minima REF NOTAM A2027/26:

  ILS CAT 2 DME 27
  Cat B: DH 100ft, RA 100ft, R 300m
  Cat C: DH 104ft, RA 104ft, R 300m
  Cat D: DH 118ft, RA 117ft, R 300m

  ILS CAT 2 DME Delta Large 27
  Cat C: DH 118ft, RA 117ft, R 300m
  Cat D: DH 118ft, RA 117ft, R 300m
  ```
- IAC/AFC Minima Minima [continues in IMG_1032]

---

## IMG_1032

**Document:** EHAM Chart NOTAM bulletin, continued (scrolled). The same left panel as IMG_1031. The top overlaps with the end of IMG_1031 (ILS CAT 2 DME Delta Large 27).

```
ILS CAT 2 DME Delta Large 27
Cat C: DH 118ft, RA 117ft, R 300m
Cat D: DH 118ft, RA 117ft, R 300m
```

**IAC/AFC Minima Minima**
```
TEMPO Minima REF NOTAM A2264/26:
27 SEP 2200-2359
28-29 SEP 0000-2359
30 SEP 0000-2200
01 OCT 2200-2359
02 OCT 0000-2200

CIRCLING RNP 04
Cat B: MDH  930ft, MDA  920ft, V 3.6km
Cat C: MDH 1030ft, MDA 1020ft, V 3.6km
Cat D: MDH 1030ft, MDA 1020ft, V 3.6km

CIRCLING RNP 09
Cat B:  C 1000ft,  MDA  920ft, V 3.6km
Cat C: MDH 1030ft, MDA 1020ft, V 3.6km
Cat D: MDH 1030ft, MDA 1020ft, V 3.6km

CIRCLING RNP 24
Cat B: C 1100ft, MDA  920ft, V 6.0km
Cat C: C 1100ft, MDA 1020ft, V 6.0km
Cat D: C 1100ft, MDA 1020ft, V 6.0km

CIRCLING all approaches (except RNP 04, RNP 09, RNP 24)
Cat B: MDH  930ft, MDA  920ft, V 1.6km
Cat C: MDH 1030ft, MDA 1020ft, V 2.4km
Cat D: MDH 1030ft, MDA 1020ft, V 3.6km
```

**IAC/AFC Minima ILS or LOC 36R**
```
TEMPO Minima REF NOTAM A2259/26:
MON-FRI 0400-1300

ILS CAT 2 DME 36R
Cat B: DH 100ft, RA 101ft, R 300m
Cat C: DH 100ft, RA 101ft, R 300m
Cat D: DH 108ft, RA 110ft, R 300m

ILS CAT 2 DME Delta Large 36R
Cat C: DH 108ft, RA 110ft, R 300m
Cat D: DH 108ft, RA 110ft, R 300m
```

**Others**
- NIL

**AMDB/AMM**
- AMDB/AMM WIP WIP
  ```
  REF SUP 30 2025
  WIP in Phases FM JAN 2026 till SEP 2027

  PHASE 26
  PRKG Stands on APN R U/S
  Access to PRKG Stand P23, P22 FM TWU Q U/S

  PHASE 26.1
  PRKG Stands on APN R U/S
  Access to PRKG Stand P23, P22 FM TWU Q U/S
  TWY B BTN TWY A28 and TWY Q CLSD

  PHASE 26.2
  TWY A BTN TWY A28 and TWY Q CLSD
  TWY Q CLSD
  TWY A BTN TWY Q and TWY A1A CLSD
  Remote HP P20-P26 AVBL
  PRKG Stands R71-R77 AVBL
  ```
  (continues in IMG_1033)

---

## IMG_1033

**Document:** EHAM Chart NOTAM bulletin, end of the scroll. The same left panel. It overlaps with IMG_1032 from "IAC/AFC Minima ILS or LOC 36R" through AMDB/AMM PHASE 26.2.

**IAC/AFC Minima ILS or LOC 36R:** same as in IMG_1032 (TEMPO Minima REF NOTAM A2259/26, MON-FRI 0400-1300; ILS CAT 2 DME 36R Cat B DH 100ft/RA 101ft/R 300m, Cat C DH 100ft/RA 101ft/R 300m, Cat D DH 108ft/RA 110ft/R 300m; Delta Large 36R Cat C/D DH 108ft/RA 110ft/R 300m).

**Others**
- NIL

**AMDB/AMM**
- AMDB/AMM WIP WIP
  ```
  REF SUP 30 2025
  WIP in Phases FM JAN 2026 till SEP 2027

  PHASE 26
  PRKG Stands on APN R U/S
  Access to PRKG Stand P23, P22 FM TWU Q U/S

  PHASE 26.1
  PRKG Stands on APN R U/S
  Access to PRKG Stand P23, P22 FM TWU Q U/S
  TWY B BTN TWY A28 and TWY Q CLSD

  PHASE 26.2
  TWY A BTN TWY A28 and TWY Q CLSD
  TWY Q CLSD
  TWY A BTN TWY Q and TWY A1A CLSD
  Remote HP P20-P26 AVBL
  PRKG Stands R71-R77 AVBL

  The actual date and time will be promulgated by NOTAM.
  ```
- AMM WIP WIP
  ```
  Applicable for mPilot

  REF SUP 30 2025
  WIP in Phases FM JAN 2026 till SEP 2027

  PHASE 26
  PRKG Stands on APN R U/S
  TWY R MAX wingspan 69M
  Access to PRKG Stand P23, P22 FM TWU Q U/S

  PHASE 26.1
  PRKG Stands on APN R U/S
  Access to PRKG Stand P23, P22 FM TWU Q U/S
  TWY R MAX wingspan 69M
  TWY B BTN TWY A28 and TWY Q CLSD

  PHASE 26.2
  TWY A BTN TWY A28 and TWY Q CLSD
  TWY Q CLSD
  TWY A BTN TWY Q and TWY A1A CLSD
  Remote HP P20-P26 AVBL
  PRKG Stands R71-R77 AVBL

  The actual date and time will be promulgated by NOTAM.
  ```

Footer: 28-09-2026

---

**Overlap notes:**
- IMG_1014 and IMG_1015 show the same takeoff calculation (Rwy Graphic ON vs OFF).
- IMG_1017, 1018, 1020, 1021 and 1022 are consecutive EHAM AOI pages 17 to 21 of 25, with small overlaps at the page edges.
- IMG_1031, 1032 and 1033 are one Chart NOTAM bulletin scrolled in three parts, with overlaps (the ILS 27 Delta Large block, and the ILS/LOC 36R through AMDB/AMM PHASE 26.2 blocks).
- The frequency box is the same on IMG_1029 and IMG_1030.
- "TWU Q" appears as written in the source (likely a typo for TWY Q).
