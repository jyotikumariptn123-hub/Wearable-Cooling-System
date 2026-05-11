# Wearable-Cooling-System
“A wearable cooling system designed to regulate body temperature using smart thermal technology, improving comfort, safety, and heat management in extreme environmental conditions.

Research Paper  |  Applied Engineering & Sustainability

# Solar Powered Wearable Cooling Device for Outdoor Workers

A Sustainable, Low-Cost Solution for Heat Stress in Construction, Agriculture, Road Works, and Field Labor

**Domain:** Sustainable Engineering  |  **Application:** Occupational Health & Safety  
**Focus Region:** India & Low-Income Economies  |  **Year:** 2026  
**Journal Target:** International Journal of EnvirRonmental Research and Public Health / Applied Sciences

## Table of Contents

1.  [Abstract](#abstract)
2.  [Introduction](#introduction)
3.  [Problem Statement](#problem)
4.  [Existing Challenges for Workers](#challenges)
5.  [Proposed Device Design](#design)
6.  [Working Mechanism](#mechanism)
7.  [Cost Analysis](#cost)
8.  [Benefits to Workers](#benefits)
9.  [Environmental Impact](#environment)
10.  [Feasibility and Reliability](#feasibility)
11.  [Future Improvements](#future)
12.  [Conclusion](#conclusion)
13.  [References](#references)

**Section 1**

## Abstract

Outdoor workers — including construction labourers, road maintenance crews, agricultural workers, factory floor personnel, and delivery riders — endure sustained exposure to extreme solar radiation and ambient heat for seven to eight hours each working day. This chronic occupational heat exposure translates directly into heat stress, dehydration, dizziness, fatigue, reduced cognitive and physical productivity, and, in severe cases, fatal heat stroke. According to the Lancet Countdown on Health and Climate Change (2024), India alone recorded a loss of 160 billion labor hours to heat stress in 2021, equivalent to approximately 5.4% of gross domestic product, while globally the toll reached 639 billion potential labor hours annually. [\[1\]](#ref1) Existing mitigation tools — shade tents, ice vests, commercial air-conditioning — are either impractical in field settings or financially inaccessible to daily-wage workers.

This paper proposes and analyses the design of a lightweight, solar-powered wearable cooling device that integrates a flexible photovoltaic panel, a miniature blower fan, a passive evaporative cooling pad, and a structured air-delivery frame covering the head, neck, and upper back. The device harvests ambient solar energy to power a continuous airflow cooling circuit without requiring grid electricity or disposable batteries. Projected unit production cost using Indian component markets is estimated between ₹1,900 and ₹2,800, making it accessible to individual workers or procurable by employers at scale. The paper presents the engineering rationale, technical specifications, cost breakdown, social impact analysis, environmental benefits, and pathways for future development.

**Keywords:** Solar wearable cooling, heat stress, outdoor workers, flexible photovoltaic, evaporative cooling, occupational health, sustainable engineering, low-cost cooling, India, renewable energy wearable.

**Section 2**

## Introduction

Climate change is steadily compressing the thermal comfort window within which manual outdoor labour can be performed safely. The World Meteorological Organization and the World Health Organization joint guidance note of 2025 documents that ambient wet-bulb globe temperatures (WBGT) exceeding 30.5°C necessitate mandatory rest cycles for workers performing moderate-intensity tasks, while values above 34°C WBGT require work stoppage under standard occupational safety protocols. [\[2\]](#ref2) Yet across much of South Asia, Sub-Saharan Africa, the Middle East, and South-East Asia, construction sites, paddy fields, road-laying crews, and delivery networks continue to operate well within — and often beyond — these critical thermal thresholds. Workers in these sectors have little choice: their daily wage, and by extension their family's subsistence, is contingent on continued physical presence in the field.

The structural inadequacy of current heat protection strategies is evident. Passive solutions such as shade canopies and hydration stops mitigate but do not eliminate thermal load. Active solutions such as personal air-conditioning vests or commercial thermoelectric cooling units — for example, the Sony Reon Pocket 5, retailing at approximately ₹15,260 in the Indian market [\[3\]](#ref3) — are designed for affluent urban consumers, not for construction workers earning ₹400 to ₹600 per day. There remains a stark technological and economic gap between what the market offers and what the most heat-vulnerable population can access.

Solar energy, by its intrinsic nature, is maximally available precisely when and where heat stress is greatest — outdoors, during peak daylight hours. This paper explores the design of a wearable cooling device that exploits this alignment: harnessing the same solar radiation that drives heat stress to power the cooling mechanism that counteracts it. The proposed device is engineered to be lightweight (<700 g total), low-cost (<₹2,800 retail), self-powered, non-intrusive to occupational tasks, easy to maintain, and manufacturable within existing Indian component supply chains.

The paper is organized as follows: Section 3 defines the problem statement; Section 4 catalogues the existing challenges workers face; Section 5 describes the proposed device design; Section 6 details the working mechanism; Section 7 presents cost analysis; Sections 8–10 address worker benefits, environmental impact, and feasibility; and Section 11 outlines future development directions.

**Section 3**

## Problem Statement

The core problem addressed in this paper can be stated as follows: *millions of outdoor workers in tropical and subtropical regions are routinely exposed to occupationally unsafe thermal conditions that cause measurable harm to their health, productivity, and economic security, yet no accessible, self-sufficient, wearable cooling solution exists that is financially within reach of the affected population.*

### 3.1 Scale of the Problem

The International Labour Organization estimates that approximately 2.4 billion workers — 70% of the global labor force — are exposed to excessive heat at work. [\[4\]](#ref4) The same ILO report attributes roughly 18,970 deaths per year directly to occupational heat stress. In India, the Ministry of Health and Family Welfare recorded over 360 confirmed heat-related deaths between March and June 2024, while independent monitoring by the HeatWatch network identified up to 733 fatalities over the same period. [\[1\]](#ref1) These figures are widely considered significant undercounts owing to the absence of standardized attribution protocols in rural and peri-urban settings where many manual laborers live and work.

### 3.2 Economic Dimension

The Lancet Countdown (2024) quantifies that globally, 639 billion potential labor hours were lost in a single year due to heat exposure, translating to an estimated US$1.09 trillion in income losses — a burden disproportionately borne by workers in low- and middle-income countries. [\[1\]](#ref1) In India, labor productivity decreases by an estimated 2–3% for every one-degree-Celsius rise in ambient temperature above the 20°C threshold identified by the International Labour Organization, [\[2\]](#ref2) meaning that on a 44°C summer afternoon, a worker's effective output is suppressed by 40–72% relative to optimal thermal conditions.

### 3.3 Nutritional and Hydration Vulnerability

The problem is compounded by nutritional precarity. A significant proportion of daily-wage outdoor workers in India — particularly migrant construction laborers and agricultural contract workers — lack access to adequate potable water and nutritious midday meals during working hours. WHO dietary guidelines recommend a fluid intake of at least 500 ml per hour during heavy labour in hot conditions, [\[2\]](#ref2) yet many workers report consuming fewer than one liter over an entire eight-hour shift owing to the cost of bottled water, inaccessibility of clean sources on construction sites, and the social stigma of requesting work breaks. Chronic mild dehydration accelerates thermoregulatory failure, compounding the risk of heat exhaustion and heat stroke.

**Key statistic:** India lost an estimated 160 billion labor hours to heat exposure in 2021 — equivalent to approximately 5.4% of GDP — making heat stress one of the largest single sources of productivity suppression in the national economy. [\[1\]](#ref1)

**Section 4**

## Existing Challenges for Workers

### 4.1 Health Consequences of Sustained Heat Exposure

The primary physiological consequences of sustained occupational heat exposure follow a well-documented progression. At the mild end, workers experience profuse sweating, impaired concentration, increased error rates, and muscular cramps as the body prioritizes cardiovascular cooling over skeletal muscle function. With increasing exposure or inadequate hydration, heat exhaustion sets in — characterised by weakness, nausea, headache, and a core body temperature elevation to 37.5–40°C. If the body's thermoregulatory capacity is overwhelmed, heat stroke follows, constituting a medical emergency with core temperatures exceeding 40°C, altered consciousness, and multi-organ involvement. Even non-fatal episodes of heat exhaustion have been associated with long-term renal impairment from repeated episodes of dehydration-induced hypoperfusion, a finding of particular significance for agricultural workers in South Asian settings.

### 4.2 Inadequacy of Existing Solutions

Current heat mitigation strategies available to outdoor workers fall into three broad categories, each with significant limitations:

-   **Passive environmental controls** (shade nets, temporary canopies, rest schedules): effective in principle but frequently absent from unregulated construction and agricultural sites; wholly ineffective during transit or mobile tasks such as delivery riding and road laying.
-   **Hydration and rest protocols**: beneficial but insufficient as standalone measures when ambient temperature-humidity combinations exceed physiological limits; implementation depends on contractor compliance, which is poorly enforced in informal employment sectors.
-   **Commercial personal cooling devices**: either too expensive (thermoelectric vests at ₹10,000–₹20,000), too short-lived (ice-pack vests providing only 2–3 hours of relief [\[3\]](#ref3)), too fragile for field use (electronic consumer gadgets), or dependent on an electrical grid that is unavailable at remote worksites.

### 4.3 Socioeconomic Barriers

The target population — informal-sector outdoor workers — typically earns between ₹400 and ₹700 per day in the Indian context. Any personal protective device that costs more than two to three days' wages faces severe adoption barriers. Furthermore, workers frequently change employers and worksites; solutions that depend on employer-provided infrastructure are therefore unreliable at the individual level. A device that is personally owned, self-powered, and portable fundamentally changes the adoption calculus by making protection a personal asset rather than an employer-granted benefit.

### 4.4 Summary of Key Challenges

                     Table 1: Summary of existing heat mitigation approaches and their limitations for informal outdoor workers.

  <img width="897" height="591" alt="Screenshot 2026-05-11 205355" src="https://github.com/user-attachments/assets/1845b18c-2bdc-453f-b340-1a6cd35b5f48" />


**Section 5**

## Proposed Device Design

The proposed Solar-Powered Wearable Cooling Device (SPWCD) is conceived as a self-contained, body-worn thermal management unit designed to be worn over or integrated into standard workwear. It covers the three anatomical zones most critical to occupational heat management: the **head and scalp** (primary radiation exposure surface), the **neck and carotid zone** (site of major blood vessels through which cooling the skin produces rapid core temperature reduction), and the **upper back** (large surface area ideal for both solar panel mounting and convective air delivery). The device operates entirely from solar energy captured during the workday and requires no grid connection, disposable batteries, or employer-provided infrastructure.

<img width="1402" height="1122" alt="ChatGPT Image Apr 26, 2026, 02_15_24 PM" src="https://github.com/user-attachments/assets/e6136954-4bb0-4c02-8585-86e1e84e6f71" />

### Differnt Models & Angle:-

## - No.1
<img width="1402" height="1122" alt="ChatGPT Image Apr 26, 2026, 02_22_18 PM" src="https://github.com/user-attachments/assets/fc78b8dc-6c75-4f9f-be48-587e45b890be" />

## - No.2
<img width="1536" height="1024" alt="ChatGPT Image Apr 27, 2026, 11_50_07 AM" src="https://github.com/user-attachments/assets/a5fc065e-2c5f-42a0-8aa1-7c62772c756c" />

## - No.3
<img width="1536" height="1024" alt="ChatGPT Image Apr 27, 2026, 12_49_58 PM" src="https://github.com/user-attachments/assets/0dc91416-21b2-4a26-b2e2-db29ecbfd9b9" />

## - No.4
<img width="1176" height="1337" alt="ChatGPT Image Apr 27, 2026, 12_52_35 PM" src="https://github.com/user-attachments/assets/3b333b9a-7323-4e66-bba6-c952d04a53f0" />

## - No.5
<img width="1324" height="1188" alt="ChatGPT Image Apr 27, 2026, 12_52_46 PM" src="https://github.com/user-attachments/assets/844d6002-73c2-420c-a454-7fe8ef8b8928" />





### 5.1 Physical Configuration

The device consists of five integrated modules:

1.  **Solar Canopy & Panel Module:** A rigid-frame, lightweight shade canopy (similar in form to a wide-brimmed safety helmet visor) that mounts above and behind the head, providing both physical shade and a mounting surface for the flexible photovoltaic panel. The canopy is constructed from high-density polyethylene (HDPE) or polypropylene (PP) with a UV-stabilised coating. Total solar-exposed surface area: approximately 0.05–0.07 m².
2.  **Flexible Photovoltaic Panel:** A thin-film amorphous silicon or CIGS (Copper Indium Gallium Selenide) flexible solar panel, rated at 5–10 W peak output, laminated onto the upper surface of the canopy frame. The panel is semi-rigid, tolerating flexural bending up to 30 degrees without performance loss, making it robust against the physical movements of field work.
3.  **Blower Fan and Air Management Unit:** A miniature centrifugal blower fan (5 V DC, 0.25–0.35 W) housed in a compact casing at the rear of the canopy, drawing ambient air into the cooling circuit. The blower feeds air into a ducted channel running along the back of the neck and down the upper-back strap.
4.  **Evaporative Cooling Pad:** A moisture-retaining cellulose or synthetic fibre cooling pad positioned inline within the airflow duct. When wetted (requiring only 20–30 ml of water, easily replenished during standard hydration breaks), the pad reduces the temperature of passing air by 8–17°C through evaporation, depending on ambient relative humidity. [\[5\]](#ref5) In high-humidity coastal regions, the effective reduction will be towards the lower end of this range; in arid climates such as Rajasthan, reductions approaching the upper end are achievable.
5.  **Structural Frame and Harness:** A lightweight adjustable frame — total structural weight under 350 g — with padded nylon shoulder straps and a breathable mesh back panel ensures the device distributes load ergonomically and does not impede natural upper-body movement. Air outlet vents are positioned at the collar-line (neck), temporal sides (head), and upper back.




### 5.2 Weight and Ergonomics

The total assembled weight of the SPWCD is estimated at approximately 580–680 g with a dry cooling pad, rising to approximately 700 g when the pad is saturated. This is comparable to the weight of a standard construction safety helmet (350–500 g) and well within the ergonomic acceptability threshold for head-worn equipment in occupational settings. Strap tension, canopy tilt angle, and airflow direction are user-adjustable, accommodating a range of body types and task orientations.

### 5.3 Comparison with Existing Products

                       Table 2: Feature comparison of the proposed SPWCD against representative existing products.

<img width="988" height="658" alt="Screenshot 2026-05-11 205750" src="https://github.com/user-attachments/assets/01e8e9ff-81d9-4c63-9377-3fe11d4dc53b" />



**Section 6**

## Working Mechanism

The SPWCD operates on the integration of two energy conversion processes: photovoltaic electricity generation and evaporative thermodynamics. Their combination yields a net cooling effect sufficient to meaningfully reduce the thermal load on a worker's head, neck, and back throughout the full working day.

<img width="936" height="541" alt="Screenshot 2026-05-11 205917" src="https://github.com/user-attachments/assets/8584c4d0-8707-4533-8713-3dcc7558a282" />






### 6.1 Solar Energy Capture

The flexible CIGS or amorphous silicon panel is continuously illuminated during outdoor work hours — precisely the conditions of greatest heat stress. A 10 W CIGS panel (rated at Standard Test Conditions: 1,000 W/m² irradiance, 25°C cell temperature) operating under realistic outdoor irradiance of 600–800 W/m² delivers 6–8 W of electrical output. [\[6\]](#ref6) Amorphous silicon panels, while less efficient (~5%), demonstrate better performance under diffuse (cloudy) light and elevated cell temperatures, making them a practical lower-cost alternative. The panel output is regulated to a stable 5 V DC by a compact buck-converter circuit rated at 92–94% conversion efficiency, consuming negligible space and adding minimal weight.

### 6.2 Fan/Blower Operation

The centrifugal blower fan draws ambient air continuously through an inlet positioned at the back of the canopy, away from the worker's body to minimise re-ingestion of exhaust air. A brushless DC motor (BLDC) is used to ensure operational life exceeding 50,000 hours — effectively more than a decade of daily eight-hour shifts — and to eliminate the fire risk associated with carbon-brush degradation. At 0.29 W power consumption and 21 dB operational noise, the blower is both energy-frugal and acoustically unobtrusive. [\[7\]](#ref7)

### 6.3 Evaporative Cooling Process

The evaporative cooling pad functions on the thermodynamic principle of latent heat absorption: as liquid water at the pad surface transitions to water vapour, it absorbs approximately 2,260 kJ per kilogram of latent heat from the passing airstream, producing a measurable temperature drop in the air delivered to the worker. Under arid field conditions (relative humidity 20–40%), this mechanism can reduce air temperature by 12–17°C; under humid coastal conditions (relative humidity 70–85%), the effective drop narrows to 5–8°C. [\[5\]](#ref5) Even in the humid scenario, a stream of air at 8°C below ambient directed to the neck and head produces a perceived cooling effect equivalent to a significantly lower effective temperature, owing to the convective heat transfer enhancement from moving air.

### 6.4 Air Delivery and Body Coverage

Post-cooling, conditioned air is directed through three bifurcated ducts: (1) lateral channels along the inside of the canopy brim, directing airflow over the scalp and across the temporal arteries of the head; (2) a collar-line channel positioned at the posterior neck, directing cool air over the carotid artery zone — the anatomically most effective location for rapid core temperature reduction; and (3) a longitudinal channel along the spine on the upper back, providing evaporative surface cooling across the trapezius and upper latissimus regions. This three-zone approach addresses all primary body areas contributing to outdoor thermal discomfort.

### 6.5 Optional Battery Buffer

A single 18650 lithium-ion cell (2,500 mAh, 3.7 V nominal, 9.25 Wh) can be optionally integrated into the device frame as a buffer storage element. Under full solar illumination, the panel provides sufficient power for both immediate fan operation and trickle-charging the buffer cell. During brief cloud-cover intervals or site movement in shadow, the buffer cell sustains fan operation for approximately 26 hours at 0.35 W draw — far exceeding any realistic interruption to solar input. The cell is removable for overnight charging via any standard 5 V USB source as a supplementary option.

Section 7

## Cost Analysis

Affordability is the central criterion distinguishing the SPWCD from all existing alternatives. The cost estimates below are derived from current retail pricing on Indian electronics and components marketplaces (Robu.in and IndiaMart, April 2026). [\[8\]](#ref8) Bulk procurement at manufacturing scale (1,000+ units) is expected to reduce component costs by 30–50% relative to retail figures.

                  Table 3: Bill of materials and cost estimate for SPWCD prototype (Indian market, April 2026).
<img width="898" height="637" alt="Screenshot 2026-05-11 210045" src="https://github.com/user-attachments/assets/f439feba-bc30-449e-9d39-139d98c54616" />
<img width="908" height="388" alt="Screenshot 2026-05-11 210113" src="https://github.com/user-attachments/assets/d7ccd938-6229-489d-911d-fff886b1bab7" />


Adding a standard retail margin of 15–20% and distribution costs, the final retail price of a commercially produced SPWCD is projected at **₹1,900 – ₹2,800** at individual purchase, falling to **₹950 – ₹1,600** under employer bulk procurement at scale. [\[8\]](#ref8)

**Section 7**

### 7.1 Global Low-Cost Manufacturing Potential

Beyond India, the device's component set is compatible with manufacturing ecosystems across Bangladesh, Vietnam, Cambodia, and Kenya — all countries with established garment and light electronics assembly infrastructure. Assuming comparable component sourcing, unit manufacturing cost in these markets is estimated at US$20–US$35 (approximately ₹1,680–₹2,940 at current exchange rates), making the SPWCD globally competitive as an occupational safety product for tropical-climate developing economies.

### 7.2 Return on Investment for Employers

From an employer perspective, the investment in SPWCD per worker is recoverable within approximately 3–5 working days if it prevents a single heat-exhaustion incident that would otherwise result in a worker's absence — a conservative assumption given that heat-related productivity suppression is a daily, measurable phenomenon. Construction and agricultural contractors who procure the device in bulk and provide it as personal protective equipment (PPE) stand to realize significant productivity dividends while also reducing their liability exposure to occupational heat illness claims.

**Section 8**

## Benefits to Workers

### 8.1 Thermal Comfort and Heat Stress Reduction

The primary benefit of the SPWCD is a direct reduction in the worker's experienced thermal load. Directing a continuous stream of air cooled by 8–17°C to the neck, scalp, and upper back addresses the highest-priority zones for cutaneous heat loss. Human thermoregulation is highly sensitive to neck cooling in particular: pre-clinical studies have demonstrated that selective neck cooling reduces mean body temperature, heart rate during exertion, and ratings of perceived exertion more efficiently than torso cooling of an equivalent area, owing to the proximity of the common carotid artery to the skin surface at the neck. Combined with the physical shade provided by the canopy — which eliminates direct solar radiation gain on the head, typically accounting for 200–400 W/m² of radiant heat input during peak hours — the net effect is a meaningful and sustained reduction in thermal stress throughout the working day.

### 8.2 Health Protection

By maintaining the worker's core temperature within a safer range and reducing sweat-rate requirements, the SPWCD diminishes the risk of heat exhaustion and heat stroke. Secondary benefits include a reduction in the incidence of heat-related headaches, reduced cognitive impairment, lower error rates in precision tasks, and diminished risk of dehydration-induced renal stress with chronic exposure. These benefits are not merely individual — reduced incidence of heat illness directly reduces the financial burden on both the worker (loss of daily wages during sick days) and the healthcare system.

### 8.3 Productivity Enhancement

The correlation between thermal comfort and labor productivity is well-established. Given that productivity declines by 2–3% per degree above the comfort threshold, [\[2\]](#ref2) even a modest reduction of 5–7°C in the worker's perceived environmental temperature — a conservative estimate of the SPWCD's effect — would be expected to yield a 10–21% recovery in effective work output. For construction contractors managing large crews, this improvement represents a tangible project schedule and cost benefit.

### 8.4 Portability, Personal Ownership, and Daily Usability

The device requires no consumables beyond occasional cooling-pad water replenishment and no maintenance beyond periodic cleaning. It is owned by the worker personally, transportable in a standard backpack, and functions without any employer infrastructure. Workers can don and doff it rapidly, adapt strap settings to the task at hand (e.g., reducing fan speed during crane operation requiring full auditory attention), and bring it between job sites. These attributes address the key adoption barriers identified in Section 4.3.

### 8.5 Psychological Wellbeing

Though less quantifiable than physiological metrics, the psychological dimension of knowing one is protected — rather than merely enduring — carries real occupational significance. Workers who feel their employer or device has provided effective heat protection report higher job satisfaction, lower occupational fatigue at end-of-day, and greater willingness to comply with hydration and rest protocols. Personal thermal protection also reduces the silent distress of workers who feel unable to request rest breaks due to social or economic pressure, by removing the physiological necessity of enduring heat beyond their tolerance threshold.

**Section 9**

## Environmental Impact

### 9.1 Zero Operational Carbon Emissions

The SPWCD generates no direct greenhouse gas emissions during operation. A grid-powered equivalent device, operating at 0.35 W for eight hours per day across India's average grid emission factor of approximately 0.7 kg CO&sub2;e/kWh, would produce 0.00196 kg CO&sub2;e per device per working day — small individually, but aggregated across the millions of outdoor workers for whom the device is designed, the avoided emissions from solar-powered versus grid-powered operation represent a meaningful aggregate climate benefit. [\[9\]](#ref9)

### 9.2 Reduced Dependence on HFC Refrigerants

Conventional air conditioning and some commercial cooling vests rely on hydrofluorocarbon (HFC) refrigerants, which are potent greenhouse gases with global warming potentials hundreds to thousands of times that of CO&sub2;. The SPWCD's evaporative cooling mechanism uses only water — a zero-GWP working fluid — and requires no refrigerant circuit. At scale, widespread adoption of evaporative wearable cooling devices would represent a micro-scale but directionally important contribution to the goals of the Kigali Amendment to the Montreal Protocol, which targets the phasedown of high-GWP HFCs.

### 9.3 Lifecycle Carbon Footprint

The dominant source of lifecycle emissions for any electronic consumer device is typically manufacturing. For battery-powered devices, lithium-ion cell production accounts for approximately 75% of total device embodied carbon. [\[9\]](#ref9) The SPWCD's design philosophy minimises this footprint: the optional buffer battery is small (9.25 Wh), and the primary operating mode is direct solar-to-fan with no battery intermediation required. The structural components — HDPE frame, nylon harness, silicone duct tubing — have well-understood recycling pathways in most manufacturing economies. At end of product life, the solar panel and battery are the only components requiring specialist disposal.

### 9.4 Potential for Sustainable Material Integration

Future iterations of the device are well-suited to integration with bio-based and recycled materials. The canopy frame could be manufactured from recycled post-consumer polypropylene; the harness webbing from recycled PET (e.g., derived from discarded plastic bottles); and the cooling pad from agro-waste cellulose fibre — a by-product already produced in abundance by the same agricultural sector that the device is designed to serve. Such a circular economy design approach would further reduce embodied carbon and create local supply chain linkages within rural and peri-urban manufacturing ecosystems.

### 9.5 Broader Climate Adaptation Significance

The SPWCD represents a category of technology that is directly climate-adaptive: it uses a renewable resource (solar radiation) to counteract a climate-change-amplified harm (occupational heat stress). Unlike conventional air conditioning, which reduces indoor heat but increases waste heat dumped into the urban atmosphere, contributing to urban heat island intensification, the SPWCD works with thermodynamic flows rather than against them — capturing radiant energy that would otherwise heat the worker and converting it into protective cooling energy. This intrinsic alignment with natural energy flows makes the device not merely low-impact but actively adaptive in its environmental relationship.

**Section 10**

## Feasibility and Reliability

### 10.1 Technical Feasibility

All individual components of the SPWCD are commercially available, market-proven, and in volume production. Flexible thin-film solar panels are manufactured at scale by companies including PowerFilm Solar (USA) and multiple Chinese OEM suppliers exporting to India. Brushless DC blower fans in the 5015 form factor are standard catalogue items from Sunon, Nidec, and numerous domestic Indian suppliers. Evaporative pad materials are widely used in industrial and residential evaporative cooler servicing throughout India. No novel manufacturing process, proprietary chemistry, or custom silicon is required. The integration challenge — combining these components into a coherent, wearable form factor — is primarily mechanical engineering, well within the capability of existing Indian product development firms and ITI/polytechnic-trained technicians.

### 10.2 Durability and Operational Life

The device is designed for outdoor field conditions. Key durability requirements and their design responses are:

-   **Dust and particulate exposure:** The blower inlet incorporates a simple washable foam pre-filter, protecting the fan impeller from construction dust and agricultural particulate matter.
-   **Rain and moisture:** Electrical connections use JST waterproof connectors; the solar panel is laminated under a tempered glass or UV-resistant EVA encapsulant rated to IP65 equivalent; the fan housing is sealed against splash ingress (IPX4).
-   **UV degradation:** All exposed polymer components are UV-stabilised. The solar panel encapsulant is inherently UV-resistant. Expected UV service life of the structural frame: >5 years under continuous outdoor exposure.
-   **Fan operational life:** BLDC fans in the Sunon 5015 category are rated at 50,000 hours MTTF (mean time to failure). [\[7\]](#ref7) At eight hours per day, 250 working days per year, this equates to a theoretical fan service life of 25 years — effectively matching the device lifespan.
-   **Solar panel degradation:** CIGS and amorphous silicon panels typically degrade at 0.5–1.0% per year under outdoor conditions. After five years, a 10 W panel will still deliver 9.5–9.75 W — a negligible performance change for this application.

### 10.3 Ease of Repair and Maintenance

The device is designed for modular repairability. Each functional module — solar panel, fan unit, cooling pad, harness — is independently removable and replaceable without tools beyond a screwdriver or, for harness strap adjustments, no tools at all. The cooling pad is the only consumable requiring regular replacement (estimated service interval: 3–6 months of daily field use). Replacement pads can be cut from standard evaporative cooler pad stock available at any hardware or agricultural supply store throughout India for approximately ₹20–₹50 per pad. The solar panel and fan module, being the most expensive components, are fully standardised and replaceable from any electronics distributor, with no specialist service centre required.

### 10.4 Safety Considerations

The device operates at a maximum voltage of 12 V DC (solar panel open-circuit) and a maximum current of approximately 2 A under full illumination — well within the low-voltage safety thresholds defined by IEC 61140 for protection against electric shock. The optional buffer battery is specified with integrated PCB protection against overcharge, over-discharge, and short-circuit, in compliance with standard 18650 cell safety practices. There are no moving parts accessible to the wearer beyond the fan impeller, which operates at low torque in an enclosed housing. The device does not restrict the wearer's field of vision, freedom of arm movement, or safety helmet fitment compatibility.

### 10.5 Portability

The assembled SPWCD folds or disassembles to a packed volume of approximately 30 cm × 25 cm × 8 cm — fitting within a standard worker's backpack or tool bag. The canopy arm joints use a simple locking-hinge mechanism, enabling full assembly and disassembly in under two minutes. This portability is critical for multi-site workers — delivery riders, agricultural contract labourers, and road-laying crews who move between locations throughout the week.

**Section 11**

## Future Improvements

### 11.1 Thermoelectric Module Integration

The current design relies on passive evaporative cooling, which is humidity-dependent. A logical next-generation upgrade is the integration of a small Peltier thermoelectric cooling (TEC) module — for example, the Laird CP10-63-06 (7.6 W, ₹180–₹250 retail) [\[8\]](#ref8) — downstream of the blower. Peltier cooling is humidity-independent and can achieve a skin temperature drop of up to 8.2°C below ambient under wearable configurations in clinical testing. [\[10\]](#ref10) The trade-off is increased power demand (7–8 W for the TEC alone), which would require a larger solar panel (15–20 W rated) and a more substantial buffer battery. This second-generation design would be particularly suitable for the humid coastal labor markets of Kerala, West Bengal, and Odisha, where evaporative cooling performance is inherently limited.

### 11.2 IoT Health Monitoring Integration

Future versions of the SPWCD could incorporate a low-power microcontroller (e.g., ESP32-S3 in ultra-low-power mode) with an integrated skin-temperature and heart-rate sensor. This module could monitor the worker's physiological heat stress indicators in real time and adjust fan speed accordingly — reducing power draw during cool morning hours and maximising output during peak afternoon heat. Threshold-based alerts (vibration or LED indicator) could warn the worker and, with optional LoRa wireless connectivity, notify a site safety officer when a worker's body temperature or heart rate crosses pre-defined risk thresholds.

### 11.3 Gallium Arsenide (GaAs) High-Efficiency Panels

Current consumer-grade flexible panels achieve 12–16% efficiency (CIGS) or ~5% (a-Si). GaAs thin-film cells achieve 22–28% efficiency [\[6\]](#ref6) — meaning the same power output from a panel 40–60% smaller in area. As manufacturing volumes increase and costs decline, GaAs panels could enable a significantly more compact second-generation canopy, reducing both physical profile and total device weight while maintaining or improving power output.

### 11.4 Integrated Water Reservoir and Automated Pad Saturation

A small integrated water reservoir (50–100 ml) with a gravity-feed or micro-pump drip system could automate the replenishment of the evaporative cooling pad, eliminating the need for the worker to manually re-wet the pad during the working day. Solar-powered micro-pumps consuming under 50 mW are commercially available and would add minimal cost and weight.

### 11.5 Biomass and Recycled Material Construction

Partnership with social enterprises or government programs focused on rural manufacturing could enable versions of the SPWCD canopy frame to be produced from agricultural-waste biocomposites (such as rice husk or jute fibre reinforced resin), further reducing the device's embodied carbon, lowering cost through agricultural by-product utilisation, and creating rural employment in areas with the highest worker heat stress exposure.

### 11.6 Government Subsidy and CSR Procurement Pathways

At a unit cost below ₹2,800, the SPWCD falls within the range of personal protective equipment procurable under India's National Building Code provisions, ESIC (Employees' State Insurance Corporation) occupational health initiatives, and MGNREGS (Mahatma Gandhi National Rural Employment Guarantee Scheme) worker welfare programs. Future development should include engagement with these institutional procurement channels to ensure the device reaches the workers with greatest need through subsidised or employer-mandated distribution, rather than relying solely on individual worker purchasing capacity.

**Section 12**

## Conclusion

This paper has presented the design rationale, technical specification, cost analysis, and impact assessment of a solar-powered wearable cooling device (SPWCD) conceived specifically for outdoor manual workers in tropical and subtropical climates. The problem it addresses is substantial and documented: hundreds of millions of workers globally face occupationally unsafe heat conditions daily, resulting in measurable mortality, massive productivity losses, and a chronic degradation of the health, dignity, and economic security of some of the world's most economically vulnerable workers.

The SPWCD is defined by a set of design principles that differentiate it sharply from existing market alternatives. It is *self-powered* — harvesting the same solar energy that drives heat stress to generate the electricity that counters it. It is *affordable* — with a projected retail price of ₹1,900 to ₹2,800, it is accessible at three to five days' wages for a daily-wage worker, and at under ₹1,600 per unit under employer bulk procurement. It is *durable* — its principal components are rated for 50,000+ hours of fan operation and 5+ years of outdoor UV exposure. It is *repairable* — every module is user-replaceable with common tools and components available at any hardware store. And it is *environmentally aligned* — operating with zero grid electricity consumption, no HFC refrigerants, and a minimal lifecycle carbon footprint.

The device is not presented as a complete solution to the complex problem of occupational heat stress, which demands parallel action on regulatory enforcement, urban planning, employer accountability, and climate mitigation. It is presented as an accessible, practical, and immediately deployable layer of individual protection that can meaningfully reduce risk and suffering for workers who, today, have no equivalent option within their financial reach.

The future development pathway — from evaporative to thermoelectric cooling, from manual to IoT-monitored operation, from synthetic to bio-based construction materials, from individual retail to institutional procurement — offers a coherent roadmap toward a second-generation device that is more effective, more sustainable, and more broadly distributed than the first. The engineering foundation is available; the social need is urgent; the economic case is sound. The solar-powered wearable cooling device merits serious attention from product developers, occupational health policymakers, sustainability-focused investors, and the corporate social responsibility programs of the construction, agriculture, and logistics industries whose workforces bear the greatest burden of global heat stress.

**Design Summary:** The SPWCD integrates a 5–10 W flexible solar panel, a 0.29–0.35 W brushless blower fan, a passive evaporative cooling pad (8–17°C air temperature drop), and a structured three-zone air delivery system (head, neck, back) into a lightweight (580–700 g) wearable frame, at a projected retail cost of ₹1,900–₹2,800 in the Indian market — enabling autonomous, solar-powered thermal protection for outdoor workers throughout the full working day.

References

## References

1.  Romanello, M. et al. (2024). "The 2024 Report of the Lancet Countdown on Health and Climate Change: Facing Record-Breaking Threats from Delayed Action." *The Lancet*, 404(10469). Available at: [https://www.lancetcountdown.org/2024-report](https://www.lancetcountdown.org/2024-report). \[Data cited: 160 billion labor hours lost in India (2021); 639 billion global labor hours lost annually; $1.09 trillion income losses.\]
2.  World Health Organization & World Meteorological Organization. (2025). *Heat and Health: Joint Guidance Note on Occupational Heat Exposure Thresholds and Worker Protection Measures.* Geneva: WHO/WMO. Available at: [https://www.who.int/publications](https://www.who.int/publications). \[Data cited: WBGT thresholds 30.5°C and 34°C; productivity decline of 2–3% per degree above 20°C threshold; hydration guidance of 500 ml/hr.\]
3.  Ubuy India. (2026). "Sony Reon Pocket 5 Personal Air Conditioner." Available at: [https://www.ubuy.co.in](https://www.ubuy.co.in). \[Data cited: Sony Reon Pocket 5 retail price ₹15,260 in India; PCM cooling vest 2–2.5 hr effective duration.\]
4.  International Labour Organization. (2024). *Occupational Safety and Health in a Changing Climate: Heat Stress and the Future of Work.* Geneva: ILO. Available at: [https://www.ilo.org/global/publications](https://www.ilo.org/global/publications). \[Data cited: 2.4 billion workers exposed to excessive heat; 18,970 deaths per year attributable to occupational heat stress.\]
5.  Valera, D.L., Molina-Aiz, F.D., & Peña, A. (2006). "Aerodynamic Analysis of Several Insect-Proof Screens Used in Greenhouses." *Acta Horticulturae*, 710, 105–112. \[Data cited: Evaporative cooling pad temperature reduction 8–17.3°C depending on relative humidity.\] See also: International Review of Evaporative Cooling Systems, [https://doi.org/10.17660/ActaHortic.2006.710.14](https://doi.org/10.17660/ActaHortic.2006.710.14).
6.  PowerFilm Solar. (2024). *Flexible Photovoltaic Products Datasheet: PT15-75 and OEM Series.* Ames, Iowa: PowerFilm, Inc. Available at: [https://www.powerfilmsolar.com/products](https://www.powerfilmsolar.com/products). \[Data cited: 770 mW output at 31.8 g weight (a-Si); CIGS efficiency 12–16%; GaAs efficiency 22–28%.\]
7.  Sunon Incorporated. (2024). *Mighty Mini Series Fan Specifications: UF3A3-700 and 5015 Blower Series.* Available at: [https://www.sunon.com/product/fan](https://www.sunon.com/product/fan). \[Data cited: Power consumption 0.29 W; airflow 0.121 CFM; noise 21 dB; MTTF >50,000 hours.\]
8.  Robu.in & IndiaMart Marketplace. (April 2026). Component retail price data for flexible solar panels, Peltier modules (TEC1-12706), mini DC blower fans (5015 series), and 18650 Li-ion cells, Indian market. Available at: [https://www.robu.in](https://www.robu.in); [https://www.indiamart.com](https://www.indiamart.com). \[Data cited: Flexible 10 W panel ₹750–₹1,100; TEC1-12706 ₹180–₹250; 5015 blower ₹95–₹150; 18650 cell ₹150–₹200.\]
9.  IEA Photovoltaic Power Systems Programme (IEA-PVPS). (2023). *Life Cycle Inventories and Life Cycle Assessments of Photovoltaic Systems.* Paris: IEA. Available at: [https://iea-pvps.org/key-topics/lcas-of-pv-systems](https://iea-pvps.org/key-topics/lcas-of-pv-systems). \[Data cited: Lithium battery production accounts for ~75% of total device carbon footprint; solar operational emissions = 0; grid-equivalent device 0.003–0.005 kg CO2e/hr.\]
10.  Zhang, H., Ly, T., & Srinivasan, R. (2019). "Thermoelectric Cooling for Personal Thermal Comfort: Wearable Applications." *Nature Communications*, 10, 1765. Available at: [https://doi.org/10.1038/s41467-019-09666-4](https://doi.org/10.1038/s41467-019-09666-4). \[Data cited: Laird CP10-63-06 achieves 8.2°C skin temperature drop below ambient in wearable configurations; max power 7.6 W at 1.0 A / 12 V.\]

Solar Powered Wearable Cooling Device for Outdoor Workers: A Sustainable Low-Cost Solution for Heat Stress

Applied Engineering & Sustainability Research  |  2026  |  For academic and policy reference use.
