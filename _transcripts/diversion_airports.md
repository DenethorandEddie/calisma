# Diversion airports around EHAM for B737-800 (research notes, 2026-09-28)

**Not for operational use.** The official AIPs (LVNL eAIP, skeyes eAIP, DFS AIP) were **not reachable** from this environment. The network egress proxy blocked eaip.lvnl.nl, ops.skeyes.be, aip.dfs.de, SkyVector, OpenNav, Wikipedia and similar sites. The data comes from:
1. **OurAirports** CSV data from the GitHub mirror, retrieved 2026-09-28. This supplied coordinates, elevation, runway physical length and width, surface, displaced thresholds and threshold coordinates.
2. **Web-search result snippets**, which quote AIP pages, airport websites and secondary aggregators. They supplied the RFFS category, operating hours and approach types.
3. **My own calculations**:
   - Great-circle distance and initial true bearing from the EHAM ARP (52.308601N, 004.763890E), using a spherical Earth with R = 3440.065 NM.
   - Magnetic QFU = true runway bearing from the threshold coordinates minus the WMM2025 variation at 2026.74 (about 2.6 to 3.9 deg E).

I could not get TORA or LDA from the AIP, except for EBAW. Where a displaced threshold is known, the JSON gives "physical length minus displaced threshold" as an **estimate only**. Check every value against the current AIP, NOTAMs and company performance data (OPT/QRH) before you use it.

B737-800 requires ICAO RFFS **CAT 7**.

| ICAO/IATA | Name | Elev ft | Dist NM / True brg from EHAM | Runways (magnetic QFU, physical length x width m, surface) | Approaches (as found) | RFFS | Hours / restrictions |
|---|---|---|---|---|---|---|---|
| EHAM/AMS | Amsterdam Schiphol | -11 | 0 (ref) | 04/22 (039/219) 2020x45; 06/24 (055/235) 3439x45; 09/27 (084/264) 3453x45; 18C/36C (180/000) 3300x45; 18L/36R (180/000) 3400x45; 18R/36L (180/000) 3800x60; all asphalt | All runways have ILS (Schiphol). LOC 06 111.55, 22 109.50, 18C 110.10, 18R 110.55, 36C 109.15, 36R 113.95 (hobbyist list). CAT ratings unverified | unverified (expected 10) | H24 (unverified) |
| EHRD/RTM | Rotterdam The Hague | -15 | 24.3 / 210 | 06/24 (054/234) 2200x45 asp, 200 m displaced thr both ends | ILS CAT I/DME 06 and 24 | unverified | 0600-2200 LT (eAIP AD 2.3) |
| EHLE/LEY | Lelystad | -13 | 28.9 / 072 | 05/23 (045/225) 2700x45 asp | RNP 23; ILS installed 2018, status unverified | unverified | No commercial ops yet (target Oct 2027). IFR Mon-Fri 0830-1630 LT, 24 h PPR (may be outdated). Emergency only |
| EHEH/EIN | Eindhoven (mil/civ) | 74 | 56.3 / 156 | 03/21 (032/212) 3000x45 asp, 250 m displaced thr | ILS Z 03, ILS 21, RNP Z 21 | CAT 8 (secondary) | Civil approx. Mon-Fri 0645-2245, Sat 0800-2000, Sun 1000-2200 LT (secondary, conflicting) |
| EHGG/GRQ | Groningen Eelde | 17 | 82.0 / 053 | 05/23 (049/229) 2500x45 asp | ILS CAT I 23 (LOC 109.90), RNP 05/23 | **CAT 5 in hours; 6-9 H24 on PPR** | Weekdays 0600-2400 LT since 1 Nov 2025; emergency accepted outside hours |
| EHBK/MST | Maastricht Aachen | 375 | 91.9 / 156 | 03/21 (029/209) 2750x45 asp, 250 m displaced thr | ILS/DME 03 and 21; CAT II/III practice on request | CAT 7 (maa.nl) | 0600-2300 LT (ext. to 0000); night PPR |
| EBBR/BRU | Brussels | 175 | 85.1 / 187 | 01/19 (012/192) 2987x50; 07L/25R (063/243) 3638x45 (50?); 07R/25L (067/247) 3211x45; asp | ILS CAT II/III 25L, 25R; ILS 01 (CAT I?); 07L/07R non-precision (unverified) | CAT 10 (secondary) | H24; night 2300-0559 LT slot/QC rules |
| EBAW/ANR | Antwerp Deurne | 39 | 68.0 / 190 | 11/29 (107/287) 1510x45 asp. **TORA 1510; LDA 11 = 1366, 29 = 1510** | ILS CAT I 29, RNP (LPV) 11, RNP 29 | CAT 7 (secondary) | 0630-2300 LT. **Too short for normal B738 ops** |
| EBLG/LGG | Liège | 659 | 103.4 / 166 | 04R/22L (042/222) 3690x45; 04L/22R (042/222) 2340x45; asp | ILS CAT III 04R and 22L; RNP 04L/22R | unverified | H24 |
| EDDL/DUS | Düsseldorf | 147 | 96.3 / 129 | 05R/23L (049/229) 3000x45; 05L/23R (049/229) 2700x45; concrete, 300 m displaced thr | ILS CAT II/III 23L, 23R, 05R | unverified | Noise rules: landings 0600-2300 (delayed to 2330, home carriers 2400); emergencies exempt |
| EDDK/CGN | Cologne Bonn | 302 | 124.0 / 133 | 13L/31R (134/314) 3815x60 asp; 06/24 (061/241) 2459x45 con; 13R/31L (134/314) 1863x45 asp | ILS on 13L/31R and 24 (category unverified); RNP only on 06, 13R, 31L | unverified | H24. Runways renamed from 14L/32R and 14R/32L on 18 Apr 2024 |
| EDDW/BRE | Bremen | 14 | 153.1 / 072 | 09/27 (084/264) 2634x45 asp, about 300 m displaced thr; 05/23 700x23 (unusable) | ILS CAT II/III 27 (IIIB, RVR 75 m) and 09; RNP/GLS | unverified | Night restriction 2230-0600 LT; 24 h obligation for emergencies |

## Key points for B737-800 planning
- **Best all-weather, H24 options:** EBBR, EBLG and EDDK (CAT III ILS, long runways, H24). EDDL has CAT III but night noise rules apply. EDDW has CAT III but is the farthest (153 NM).
- **EHGG:** the published RFFS is only CAT 5 during opening hours. You need PPR to get CAT 7 fire cover.
- **EHLE:** not open to commercial traffic. Use it for emergencies only.
- **EBAW:** LDA of 1366 to 1510 m. Use it for emergencies only.
- **EHRD:** CAT I only, and the LDA is about 2000 m. Performance may be limiting on a wet runway.
- **Military airfields** such as EHWO were skipped, as requested.

## Sources
- OurAirports data (GitHub mirror): https://github.com/davidmegginson/ourairports-data (airports.csv, runways.csv)
- LVNL eAIP (seen only as search snippets): https://eaip.lvnl.nl/web/eaip/ (EHAM, EHRD AD 2.3, EHBK, EHGG, EHLE pages)
- skeyes eAIP (seen only as search snippets): https://ops.skeyes.be/html/belgocontrol_static/eaip/eAIP_Main/html/eAIP/EB-AD-2.EBAW-en-GB.html, EB-AD-2.EBLG, EB-AD-2.EBBR
- Schiphol, "Which landing systems do Schiphol runways have": https://www.schiphol.nl/en/schiphol-as-a-neighbour/which-landing-systems-do-schiphol-runways-have
- Schiphol frequency list (hobbyist): https://www.qsl.net/pd1e/schiphol/
- EHRD AIP IAC chart titles: https://opennav.com/pdf/EHRD/EH-AD-2.EHRD-IAC-06-1.pdf, https://opennav.com/pdf/EHRD/EH-AD-2.EHRD-IAC-24-1.pdf
- Groningen Airport hours: https://www.rtvnoord.nl/economie/1361244/, https://www.rijksoverheid.nl/actueel/nieuws/2025/10/28/luchthavenbesluit-groningen-airport-eelde-gepubliceerd
- EHGG RFFS: https://skyvector.com/airport/EHGG/Groningen-Eelde-Airport, http://ourairports.com/airports/EHGG/pilot-info.html
- Lelystad status: https://nltimes.nl/2026/04/19/dutch-government-targets-2027-opening-lelystad-airport-pending-nature-permit, https://airport-data.com/world-airports/EHLE-LEY/
- Maastricht hours and RFFS: https://www.maa.nl/operatie/, https://www.maa.nl/bhv-erkenning-brandweer-maa/
- Eindhoven: https://www.businessairnews.com/hb_airportpage.html?recnum=1076, https://notamify.com/notams/EHEH/47178540-5cba-4f8b-ba49-193c46334c36
- Brussels: https://www.scribd.com/document/656320848/EBBR-Brussels-Airport, https://www.brusselsairport.be/en/neighbours-and-spotters/faq
- Antwerp: https://www.scribd.com/document/656320844/EBAW-Antwerp-Intl-Airport, https://www.antwerp-airport.com/about-antwerp-airport/
- Düsseldorf: https://www.dus.com/de-de/konzern/nachbarn/transparenz/flugbetrieb/betriebszeiten, https://nav.vatsim-germany.org/files/edgg/charts/eddl/public/EDDL_ILS23L.pdf
- Cologne Bonn: https://www.cologne-bonn-airport.com/en/company/newsroom/press-releases/detail/runways-to-be-renamed.html, https://knowledgebase.vatsim-germany.org/books/airports-langen-fir-edgg/chapter/eddk-kolnbonn/export/html
- Bremen: https://umwelt.bremen.de/umwelt/laerm/fluglaerm/fluglaerm-haeufige-fragen-2387344, https://nav.vatsim-germany.org/files/edww/charts/eddw/public/EDDW_IAC_ILS_RWY27.pdf
- Magnetic variation: NOAA/BGS World Magnetic Model 2025 (pygeomag)
