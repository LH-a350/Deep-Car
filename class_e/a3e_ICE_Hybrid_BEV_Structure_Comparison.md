# Lesson 3: In-depth Comparison of Overall Structures for ICE Vehicles, Hybrid Vehicles and BEVs
## Learning Objectives of This Lesson
- *Clarify the essential architectural differences among the three vehicle types based on the underlying logic of energy flow;*
- *Distinguish general components and exclusive parts for each of the four major assemblies, identifying universally applicable systems and completely independent systems;*
- *Master the core structural differences among series hybrid, parallel hybrid and power-split hybrid systems, correlating with niche precision components such as gear sets and coupling mechanisms;*
- *Establish basic understanding of structural complexity, maintenance costs and part compatibility, laying a foundation for subsequent comparison of advantages and disadvantages among component brands.*

<kbd> https://www.github.com/LH-a350/Deep-Car </kbd>

## 1. Fundamental Differences Among Three Vehicle Types: Energy Flow Path
***The root cause of all structural discrepancies lies in different conversion paths of energy from storage to wheel propulsion:***
- **ICE Vehicles**:
`Chemical energy of gasoline → Thermal energy from cylinder combustion → Linear mechanical energy of pistons → Rotational mechanical energy of crankshaft → Torque amplification via transmission gears → Wheel propulsion
Two energy conversion processes in total with substantial thermal losses, featuring the most complex mechanical transmission structure;
Power output fully relies on coordination between internal combustion engine and multi-speed transmission.`

- **Battery Electric Vehicles (BEVs)**:
`Chemical energy of lithium battery → Electric energy → Three-phase alternating current inverted by motor controller → Rotational mechanical energy of drive motor → Speed reduction and torque amplification via reducer → Wheel propulsion
Only one conversion from electric energy to mechanical energy, with energy efficiency 2–3 times higher than ICE vehicles;
No combustion, no exhaust system and no complex multi-speed gear sets, delivering an extremely simplified mechanical structure.`

- **Hybrid Vehicles**:
`Equipped with two power sources (internal combustion engine + electric motor). Energy flow paths can be switched or superimposed according to operating conditions, balancing low fuel consumption and long driving range.
Hybrid structure combines configurations of ICE vehicles and BEVs with additional power coupling mechanisms, resulting in the highest overall structural complexity.`

## 2. Horizontal Comparison of Four Major Assemblies (General Parts + Exclusive Parts + Labeled Niche Components)
### 2.1 Powertrain Assembly (Core Section with Maximum Differences)
| Vehicle Type | Core Exclusive Components | General Basic Components | Corresponding Niche Precision Components |
| :--- | :--- | :--- | :--- |
| ICE Vehicle | Complete engine assembly, turbocharger / intercooler, fuel supply system, exhaust three-way catalytic converter, multi-speed transmission | Differential, half shaft, final drive gear | VVT phase adjustment gear, turbo floating bearing, intercooler flow divider baffle, oil pump gear, synchronizer ring |
| BEV | Drive motor, traction battery pack, Motor Control Unit (MCU), single-speed reducer, On-Board Charger (OBC) | Differential, half shaft, final drive gear | Reducer helical gear set, motor rotor floating bearing, high-voltage bus contactor, battery cooling check valve |
| Hybrid Vehicle | Engine + single/dual electric motors, power coupling mechanism, high-voltage battery pack, Power Distribution Unit (PDU), DC-DC converter | Differential, half shaft, final drive gear | Planetary gear set (core of power split system), separating clutch gear, generator stator insulator, high-voltage interlock switch |

> Key Conclusion:
> The differential, half shaft and final drive gear at the rear end of the chassis share identical basic structures for all three vehicle types, differing only in dimensions and strength parameters. All discrepancies concentrate on the "power source" and the front section of power transmission.

### 2.2 Chassis Assembly (Assembly with Highest Part Compatibility)
- **90% of components are universal**:
`Suspension control arms, shock absorber springs, steering gear, brake system, wheels and tires adopt consistent basic principles and structures.
Corresponding niche components: steering rack and pinion gear, brake master cylinder piston seal, suspension rubber bushing, differential bevel gear. Brand performance of these parts can be referenced across all three vehicle categories.`

> Core Differences:
>- Layout Space: `ICE/hybrid chassis must reserve routing space for exhaust pipes and fuel tanks; BEVs carry battery packs laid flat at the chassis center, achieving lower center of gravity and flatter floor panels.`
>- Brake Boost: `ICE vehicles utilize intake vacuum boost from the engine; BEVs have no vacuum source and mostly adopt electronic brake booster systems (iBooster).`
>- Load Weight: `BEV battery packs add considerable weight, requiring higher strength design for suspension springs and bearings. Standard ICE components cannot be directly replaced onto BEVs.`

### 2.3 Body Assembly (Highest Structural Overlap Rate)
- **Universal Sections**:
`Body frame, door structure, A/B/C pillars, crash energy absorption design, cabin interior and seat frames follow unified design standards for all three vehicle types.`

> Detailed Differences:
>- Front Compartment Layout: `BEVs have no engine, allowing front luggage compartment layout and simplified firewall structure; ICE/hybrid front compartments feature dense pipelines and more cooling components.`
>- Bottom Protection: `BEVs install high-strength under-shields under battery packs to prevent impact and puncture; ICE vehicles are mostly coated with sound insulation and anti-corrosion materials at the bottom.`
>- Niche Small Components: `BEV exclusive battery pack sealing strips, explosion-proof pressure relief valves; ICE exclusive engine compartment sound insulation deflectors.`

### 2.4 Electrical & Electronic Assembly (Clear Boundary Between Two Voltage Systems)
- **Universal Low-Voltage 12V System**:
`Lights, window regulators, instrument panel, central control unit, body controller, 12V storage battery are fully compatible among all vehicle types.`

> Exclusive High-Voltage System (Unique to BEVs & Hybrids):
>- High-voltage wiring harness, Vehicle Control Unit (VCU), Battery Management System (BMS), On-Board Charger (OBC)
>- Niche Precision Components: `High-voltage pre-charging resistor, insulation monitoring sensor, current sensor, Maintenance Service Disconnect (MSD)`

***ICE vehicles adopt only 12V low-voltage power supply without high-voltage systems, featuring the simplest electrical structure. Hybrid vehicles integrate both 12V low-voltage and high-voltage systems, resulting in the most complex wiring layout.***

## 3. In-Depth Structural Classification of Three Hybrid Technical Routes (Special Topic on Core Gear Mechanisms)
***The core distinction among hybrid systems lies in how the engine and electric motors coordinate to output power, which directly determines the complexity of gear mechanisms and maintenance costs.***
### 3.1 Series Hybrid (Extended-Range EV)
- **Structural Logic**:
`The engine is only connected to the generator for power generation and is completely isolated from wheels; wheels are 100% driven by the traction motor.`
- **Power Path**:
`Engine → Generator → Battery / Motor Controller → Drive Motor → Reducer → Wheels`
- **Core Components**:
`Generator, drive motor, single-speed reducer; no complex mechanical gear coupling mechanisms.`

> Representative Models: Li Auto L Series, AITO Extended-Range Models
> Advantages & Disadvantages: `Excellent low-speed smoothness, simple structure and low failure rate; the engine cannot directly drive wheels under high-speed conditions, leading to high losses from secondary energy conversion.`
> Niche Components: `High-speed generator rotor bearing, sealed terminals of high-voltage three-phase wiring harness.`

### 3.2 Parallel Hybrid
- **Structural Logic**:
`The engine and electric motor are connected in parallel on the same input shaft via a clutch, capable of independent driving or combined power output.`
- **Core Components**:
`Separating clutch, transmission input shaft gear, multi-speed transmission gear set`

> Power Modes: `Pure Electric Mode (clutch disengaged, motor drives independently), Hybrid Mode (clutch engaged, engine and motor output power jointly), Engine Direct Drive (high-speed operating conditions)`
> Representative Models: BYD DM-i, partial PHEV models of Volkswagen and Toyota
> Advantages & Disadvantages: `High efficiency under direct engine drive at high speeds and strong power; frequent clutch switching at low speeds tends to cause jerk and greater impact during gear meshing.`
> Niche Components: `Clutch friction steel plates, input shaft synchronizer ring, dual mass flywheel gear.`

### 3.3 Power-Split Hybrid (Planetary Gear Type)
- **Structural Logic**:
`Centered on a planetary gear set. The engine, generator and drive motor are separately connected to three components of the planetary set. Motor speed regulation realizes continuously variable transmission without conventional gear shifts.`
- **Core Niche Components**:
`Planetary gear set composed of sun gear, planet carrier and ring gear; gear precision directly determines driving smoothness and service life.`

> Representative Models: Toyota THS Hybrid, GM Voltec Hybrid
> Advantages & Disadvantages: `Ultimate smooth driving, stable fuel consumption and no shift jerk; extremely high precision requirements for planetary gear machining. Aftermarket parts rarely meet standards, requiring OEM or tier-one OEM matching parts for maintenance.`
> Brand Comparison Prelude: `OEM planetary gear sets are mostly supplied by Schaeffler and Bosch with small gear backlash, outstanding wear resistance and low noise. Generic aftermarket replicas generally suffer insufficient tooth surface heat treatment and tend to generate abnormal noise and wear within 30,000–50,000 kilometers.`

## 4. Comparison of Structural Complexity and Maintenance Characteristics
> Ranking & Rule Summary:
>- **Structural Complexity Ranking**: `Power-split Hybrid > Parallel Hybrid > ICE Vehicle > Series Extended-Range Hybrid > BEV`
>- **Part Compatibility Ranking**: `Chassis Wear Parts > Body Parts > Low-Voltage Electrical Parts > Exclusive Powertrain Parts`
`Universal parts including brake pads, tires, suspension bushings and storage batteries can adopt the same brand across three vehicle types, applicable for subsequent brand comparison lessons;
Internal engine components, three-electrical components and hybrid coupling mechanisms are completely incompatible, with independent supporting brand systems respectively.`

> Maintenance Cost Rules:
>- General Parts: `Prices are transparent. Tier-one brands (Bosch, Mahle, Sachs etc.) cost 30%~80% higher than aftermarket generic parts with obvious advantages in service life and stability;`
>- Exclusive Core Parts: `Three-electrical components, planetary gears, turbochargers and intercoolers are dominated by OEM / tier-one suppliers. Limited aftermarket alternatives lead to high maintenance expenses.`

## 5. Component Summary of This Lesson (To Be Disassembled In-Depth in Subsequent Special Lessons)
1. Planetary Gear Set (Core Transmission Component of Power-Split Hybrid Systems)
2. Helical Gear Set of Motor Reducer
3. High-Voltage Pre-Charging Resistor, High-Voltage Interlock Switch
4. Clutch Release Bearing and Input Shaft Gear
5. Differential Bevel Gear (Universal Core Chassis Transmission Component)

# End of Lesson