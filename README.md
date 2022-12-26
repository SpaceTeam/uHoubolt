# µHoubolt
µHoubolt is an Ethanol/N2O liquid rocket sucessfully flown at EuRoC 2022. It is capable of reaching an altitude of 3km with a 1kg payload, with a lift-off mass of only 12kg and a length of 2m.

To enable other student or amateur teams to benefit from our developments, and maybe even base their own rocket design on µHoubolt, all design ressources are available as open source/hardware.

This repository serves as an overview, containing some project ressources and linking to many others.

In case of any questions, please feel free to contact [daniel.frank@spaceteam.at](mailto:daniel.frank@spaceteam.at).

## Overview

## Ressources
While unfortunately these ressources are for a large part not very well organized nor documented (sorry!), they should contain everything needed to replicate this project.

### Documentation
- [Website](spaceteam.at/uhb)
- [Technical Report](TechnicalReport_EuRoC2022.pdf) and [LaTeX sources](TechnicalReport_EuRoC2022_Sources)
- [Launch Procedures](µHoubolt_Launch_Procedures.pdf) and [LaTeX sources](µHoubolt_Launch_Procedures_Sources)
- [BOM](BOM)
- EuRoC 2022 Flight Report
- Media

### Simulation
- [OpenRocket Liquid Engine Generator](https://github.com/SpaceTeam/ORLEG)
- [OpenRocket Simulation](Simulation_OpenRocket)

### Mechanical
- CAD Rocket
- CAD/Description Launch Pad

### Electronics + Firmware
- [Radio Communication Unit KiCAD Project](https://github.com/SpaceTeam/uHoubolt_PCB_RCU)
- [Power Management Unit KiCAD Project](https://github.com/SpaceTeam/uHoubolt_PCB_PMU)
- [LiIon Charger KiCAD Project](https://github.com/SpaceTeam/uHoubolt_PCB_LiIon_Charger)
- [Engine Control Unit KiCAD Project](https://github.com/SpaceTeam/uHoubolt_PCB_ECU)
- [KiCAD Library](https://github.com/SpaceTeam/TXV_Library_PCB)
- [RCU / PMU / ECU Firmware](https://github.com/SpaceTeam/firmware_liquids)
- [Space Team Rocket Hardware Abstraction Layer](https://github.com/SpaceTeam/STRHAL)
- [CAN Protocol](https://github.com/SpaceTeam/can_houbolt)

### Software
- [ECUI Web](https://github.com/SpaceTeam/web_ecui_houbolt)
- [ECUI LL](https://github.com/SpaceTeam/llserver_ecui_houbolt)
- [ECUI PnID](https://github.com/SpaceTeam/pnid_houbolt)
- [ECUI Theming](https://github.com/SpaceTeam/SpaceTeamTheme)
- [ECUI Config](https://github.com/SpaceTeam/config_ecui)
- [PnID KiCAD library](https://github.com/SpaceTeam/pnid-lib)

## Known Issues
Some of the ressources linked above contain known issues spcific to them. The others are listed here in no particular order.
- Documentation & procedures insufficient
- Fill system vent not great (?)
- Almost no load (or other) simulations done (officials at launch events don't like that)
- Engine efficiency inconsistent over multiple manufactured parts, injector design probably quite susceptible to tolerances
- COTS linecutters for recovery are expensive
- Oxidizer fill valve leak (see flight report)
- Drogue a little too small, large main shock
- One piece cotton phenolic chamber abalates quickly and manufacturing is time consuming A graphite nozzle and phenolic paper chamber liner would probably be better.
- Cable management not that good
- Lift-off velocity quite low, safe but quite susceptible to wind, EuRoC officials unhappy
- Launch pad oxidizer bottle installation difficult and unsafe
- Recovery lines rub against corners and need tape protection
- Eggtimer TRS mounting not great
- Launch pad oxidizer bottle temperature management difficult in hot weather
- Propulsion system transport and installation annoying due to fuel system not being structurally connected
- Threads in thin aluminium strip easily
- Fuel fill screw connection annoying
- Fuel fill syringe heavy to operate
- Cameras positioned too far inwards, require large cutouts in body tube
- Accessing avionics requires too much disassembly
- Umbilical connection not robust
- Battery charging via umbilical not working
- Battery capacity too low to support EuRoC required standby time if charging on launch rail doesn't work
- GNSS reception marginal when fully assembled
- Recovery shock absorbers worked well but need more testing & characterization
- Igniter breech PTFE seals annoying, elastomer o-rings would probably be better
- Igniter manufacturing nconsistent and depentdent on experience
