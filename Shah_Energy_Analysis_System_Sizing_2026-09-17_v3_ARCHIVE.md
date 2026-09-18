# Shah Residence — Energy Analysis & System Sizing

**Archive date:** September 18, 2026  
**Prepared by:** Thomas Cottrell, Clean Solar  
**Customer:** Pooja & Srihari Shah — Los Altos Hills, California  
**Source artifact:** Shah_Energy_Analysis_System_Sizing_2026-09-17_v3.docx  
**Status:** Final first-proposal analysis; repository-native archival record

## Executive summary
- Planning annual load: **31,750 kWh**
- Candidate PV: **20.24 kW DC**
- Aurora annual production: **30,255 kWh**
- Annual production offset: **95.3%**
- Array: **44 × REC 460 W**
- Storage: **2 × Tesla Powerwall 3 = 27 kWh nominal**
- Combined inverter output: **23 kW**
- Electrical service: **200 A**, customer-confirmed Sept. 17, 2026
- Tesla Backup Switch may provide a simpler interconnection path, subject to final site conditions, engineering, utility/AHJ requirements, and final design.

## Modeled annual load
- Baseline occupied-home model: **12,750 kWh/year**
- At-home EV charging: **9,000 kWh/year**, plus ~1,000 kWh/year assumed away from home
- AI/research compute planning allowance: **10,000 kWh/year**

## Measured-data interpretation
The available PG&E interval sample covered Sept. 12–14, 2026 and averaged about **52.7 kWh/day** while the home was essentially unoccupied. It was used diagnostically rather than annualized.
- Standing load: roughly **0.7–1.1 kW**
- Repeatable **4–7 AM** increase consistent with scheduled pool filtration
- Sustained afternoon **3–4+ kW** load consistent with air conditioning
- Pool load shifted in planning model to about **10 AM–2 PM**
- A/C treated seasonally

The final DOCX contains the added image of the actual PG&E hourly usage comparison.

## System / Aurora baseline
Corrected roof layout is the controlling physical baseline. The central roof area is left open for planned skylights.

## Charge on Solar sensitivity
| EV energy available for solar-following | Grid purchases | Reduction vs baseline | Grid dependence |
|---:|---:|---:|---:|
| 0% | 5,308 kWh | — | 16.7% |
| 25% | 4,523 kWh | 14.8% | 14.2% |
| 50% | 3,839 kWh | 27.7% | 12.1% |
| 75% | 3,284 kWh | 38.1% | 10.3% |
| **80% planning case** | **3,195 kWh** | **39.8%** | **10.1%** |
| 100% sensitivity boundary | 2,888 kWh | 45.6% | 9.1% |

At 80% EV flexibility, modeled grid purchases decline about **2,113 kWh/year (~40%)**. The 80% figure is a planning assumption, not measured behavior.

## Flexible-compute sensitivity
After the 80% EV-flexibility case:

| Compute energy available for solar-following | Grid purchases | Reduction vs original baseline | Grid dependence |
|---:|---:|---:|---:|
| 0% | 3,195 kWh | 39.8% | 10.1% |
| 25% | 2,787 kWh | 47.5% | 8.8% |
| 50% | 2,477 kWh | 53.3% | 7.8% |
| 75% | 2,240 kWh | 57.8% | 7.1% |
| 100% sensitivity boundary | 2,079 kWh | 60.8% | 6.5% |

Longer-term concept: **Solar → house loads → Powerwalls → EV charging → flexible compute → grid.**

## Economics preserved from final analysis
- Solar price: **$81,610**
- Roof-rework placeholder: **$20,000**
- PV HDM discount: **17%**
- 2 × Powerwall 3 price: **$24,762**
- Battery HDM discount: **25%**
- Gross project price shown: **$106,373**
- Total HDM discount shown: **$20,064**
- Working net price shown: **$86,309**

These figures are preserved as stated in the final analysis and are not silently reconciled to later proposal output.

## Customer questions
1. Is 80% EV solar-charging availability realistic?
2. How much AI/research compute can move several hours to follow solar?
3. Is the priority lowest lifetime cost, minimum PG&E dependence, backup resilience, future expansion, or a combination?
4. How likely is the future ADU, and on what horizon?
5. Build more capacity now or preserve an economical expansion path after a year of operating data?

## Modeling note
Grid-import and flexible-load results are planning estimates, not guarantees. Actual results vary with weather, occupancy, vehicle availability, charging behavior, computing schedules, tariff structure, equipment controls, and final system design.
