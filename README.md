<h1 align="center">
    <a href="spacelab.ufsc.br"><img src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/rocus-patch.png" alt="rocus" width="40%"></a>
    <br>
     RADIO OCCULTATION MISSION
    <br>
</h1>

<h4 align="center">A compilation of the mission documents, diagrams, spreadsheets and figures.</h4>

<p align="center">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
    <a href="http://golds.ufsc.br/en/team/">
		<img src="https://img.shields.io/badge/spacelab%20members-8-blue?style=for-the-badge">
	</a>
	<a href="#license">
		<img src="https://img.shields.io/badge/open--source-project-lightgray?style=for-the-badge">
	</a>
	<a href="http://www.inpe.br/crn/">
		<img src="https://img.shields.io/badge/partner-inpe--rn-yellow?style=for-the-badge">
	</a>
	<a href="http://ufsc.br">
		<img src="https://img.shields.io/badge/sourced%20by-UFSC-orange?style=for-the-badge">
	</a>
	<a href="https://www.gov.br/aeb/pt-br">
		<img src="https://img.shields.io/badge/sourced%20by-AEB-red?style=for-the-badge">
	</a>
    <a href="https://github.com/spacelab-ufsc/radio-occultation-doc/actions">
        <img src="https://img.shields.io/github/workflow/status/spacelab-ufsc/radio-occultation-doc/Build%20LaTeX%20document?style=for-the-badge">
    </a>
</p>

<p align="center">
  	<a href="#overview">Overview</a> •
  	<a href="#mission-statement">Statement</a> •
  	<a href="#mission-objectives">Objectives</a> •
  	<a href="#development">Development</a> •
  	<a href="#partners">Partners</a> •
  	<a href="#licenses">Licenses</a> •
  	<a href="#notes">Notes</a>
</p>


# Overview

The Radio Occultation Mission focuses on the development of a CubeSat dedicated to the acquisition of GNSS radio occultation data, expanding the national atmospheric observation capacity. The satellite will employ an L1-band GNSS front-end coupled to an FPGA/RISC-V SoC to pre-process onboard the phases and amplitudes of GNSS signals touched by the atmosphere, generating refraction angle profiles.

With its own RO data, Brazil will be able to routinely feed numerical weather prediction models, increasing the accuracy in predicting severe phenomena — such as extratropical cyclones that affect the South of the country — and reinforcing civil defense and precision agriculture strategies. The mission will also consolidate local expertise in on-board processing and miniaturization of GNSS receivers for space, creating a reusable platform for future payloads.

This documentation structure is described in the <a href="#repository-organization">repository organization</a> section.

<p align="center">
    <img width="65%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/rocus-sat.png" />
</p>

# Mission Statement

TBD

# Mission Objectives

1. TBD
2. TBD

# Development 

The following sections describe the mission subsystems, which placement, positioning and attachement can be seen in the next figure. Also, it is provided a quick review of the development status of each module throught the use of dynamic badges. The profile icons right above the module name is the GitHub contributors of this repository, which might not included all contributors to the project as a whole. Refer to the specific repositories or the website for a complete list.  

<p align="center">
  <img width="65%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/exploded-view-tbd.png" />
</p>

<br><br>

<a href="https://github.com/spacelab-ufsc/obdh2/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/ro-instrument" />
</a>

## Radio Occultation Instrument

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ro-instrument/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/ro-instrument?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ro-instrument/commits/main">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/ro-instrument?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ro-instrument/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/ro-instrument?style=for-the-badge">
	</a>
</p>

<br><br>

<a href="https://github.com/spacelab-ufsc/r0-antenna/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/ro-antenna" />
</a>


## Radio Occultation Instrument Antenna

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ro-antenna/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/ro-antenna?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ro-antenna/commits/main">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/ro-antenna?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ro-antenna/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/ro-antenna?style=for-the-badge">
	</a>
</p>

<br><br>

<a href="https://github.com/spacelab-ufsc/adcs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/adcs" />
</a>

## ADCS - Attitude Determination and Control System

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
</p>

<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/adcs.png">

Our Attitude Control System (ACS) is a passive attitude system, which uses Earth's magnetic field to rotate and stabilize the satellite. The system is composed of one magnet to create a force to align the magnet with the Earth's magnetic field and four hysteresis bars to damp the cube oscillations and stabilize. They are placed in positions to minimize the magnet effect on the bars. As a passive magnetic attitude control system is used, it is possible to stabilize only two axis, and so, the cubesat will still rotate around one of its axis, even after stabilized.

<br><br>
<br><br>


<a href="https://github.com/spacelab-ufsc/sband-antenna/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/sband-antenna" />
</a>

## S-Band Antenna

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
</p>

<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/subsystems/sband-antenna-top.png">

​The S-Band Antenna project consists of developing an antenna for the S-Band frequency (2.200-2.290 GHz), which its initial goal is to be used in a mission of Radio Occultation for the downlink of data.​

<br><br>
<br><br>
<br><br>


<a href="https://github.com/spacelab-ufsc/gnss-active-antenna/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/gnss-active-antenna" />
</a>

## GNSS Antenna

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
</p>

<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/subsystems/gnss-active-antenna-top.png">

The GNSS Active Antenna project consists of developing an active antenna for the L1 band (1.565GHz), integrating a low noise amplifier (LNA) powered by a voltage regulator that converts 5V to 3.3V, with the power being injected into the coaxial line through a bias tee circuit.

<br><br>
<br><br>
<br><br>

<!--
<a href="https://github.com/spacelab-ufsc/antenna-fd/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/" />
</a>
-->

## Filamentar Antenna

<!--
<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/antenna-fd/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/antenna-fd?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/antenna-fd/commits/main">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/antenna-fd?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/antenna-fd/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/antenna-fd?style=for-the-badge">
	</a>
</p>

-->

<a href="https://github.com/spacelab-ufsc/radio-occultation-doc">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/subsystems/antenna-fd.png">
	
</a>


<!-- <img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/antenna-fd.png"> -->

The SpaceLab Filamentar Antenna for CubeSats System 1U/3U contains up to four tape spring antennas of up to 50 cm length. The deployment system relies on a thermal knife composed of one wire and two redundant heating elements per tape. RF phasing / BalUn circuitry ties the antennas together in the user-defined configuration. Depending on the configuration, one or two radios in the CubeSat can connect to the antenna system by means of miniature RF connectors. The top face of the antenna system can accommodate a two solar cell solar panel and it can be customized for accommodating sensors or other systems to protrude to the exterior, e.g. camera apertures. The antenna is compatible with any UHF and/or VHF radio system. 

<br><br>


## Solar Panels

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-flight%20ready-green?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/purchased%20module-ORBITAL-lightgray?style=for-the-badge">
	</a>
</p>

<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/orbital-solar-panel.png">

The solar panels are manufactures by TBD. The panels features protection diodes and high-efficiency solar cells, which are the CESI's CTJ-30 with dimensions 6.9 cm x 3.9 cm (area 26.5 cm2). This cell is qualified for space use by ESA with an efficiency of 30%.

<br><br>

## USIPED - 6U Mechanical Structure

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-under%20testing-yellow?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/purchased%20module-USIPED-lightgray?style=for-the-badge">
	</a>
</p>

<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/usiped-2u-structure.jpg">

The USIPED 6-Unit CubeSat structure is developed as a generic, modular satellite structure based upon the CubeSat standard. The modular chassis allows for up to two 1-Unit stack of PCBs, or other modules, to be mounted inside the chassis, using the PC-104 standard and spacers attached to the structure. In addition, there are 4 slots in the middle section, providing space for the interface boards and the ACS. The solar panels and antennas are externally mounted, providing a complete mechanical solution.

<br><br>


# Service platform

SpaceLab FloripaSat-2 modules

<br><br>

<a href="https://github.com/spacelab-ufsc/obdh2/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/obdh2" />
</a>

## OBDH - On-Board Data Handling

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/obdh2/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/obdh2?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/obdh2/commits/main">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/obdh2?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/obdh2/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/obdh2?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/obdh2">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/obdh2/blob/main/doc/user_manual/figures/obdh2-pcb-top.png">
</a>

The SpaceLab OBDH2 (On-Board Data Handling 2.0) is one of the service modules developed for radio-occultation Cubesat Mission. The OBDH2 is responsible to synchronize actions and the data flow between other modules (ie. EPS, Payloads) and the Earth segment. It packs the generated data into data frames and transmit back to Earth through TTC module, or stores it on a non-volatile memory for later retrieval. Commands sent from Earth segment to the cubesat will be received by the radio transceivers located in the TTC module and redirected to the OBDH2, which takes the appropriate action or forward them to the responsible module. All the OBDH2 project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/obdh2) under its respective licenses.

<br><br>

<a href="https://github.com/spacelab-ufsc/ttc2/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/ttc2" />
</a>

## TTC - Telemetry, Tracking and Telecommand

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in--orbit%20validated-blue?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ttc2/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/ttc2?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ttc2/commits/main">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/ttc2?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/ttc2/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/ttc2?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/ttc2">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/ttc2/blob/master/doc/user_manual/figures/ttc2_pcb_top.png">
</a>

The TTC (or TT&C) is the communication module of the CubeSats from SpaceLab. It is responsible to make the communication between the earth (a ground station) and a satellite, and is divided in two sub-modules: Beacon and telemetry. The beacon is a independent sub-module who transmits a periodic signal containing an identification data (ID) of the satellite and some basic telemetry data. The telemetry sub-module is the main communication device. It has a bidirectional data link to receive telecommands from the earth and transmit all the requested data. The telemetry sub-module is controlled by an external device (as example, an OBDH module). All the TTC project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/ttc) under its respective licenses.

<br><br>

<a href="https://github.com/spacelab-ufsc/eps2/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/eps2" />
</a>

## EPS - Electrical and Power System

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/eps2/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/eps2?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/eps2/commits/master">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/eps2?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/eps2/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/eps2?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/eps2">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/eps2/blob/master/doc/figures/eps2-pcb-top.png">
</a>

The EPS2 has been designed to harvest, store and distribute energy for the radio-occultation CubeSat mission. The energy harvesting system is based on solar energy conversion through 10 solar panels attached to the structure. The EPS is designed to operate the solar panels at their maximum power point. The harvested solar energy is stored in 4 lithium-ion batteries connected in series/parallel. The energy distribution is done by several integrated DC-DC converters. The full EPS system is composed of the solar panels, the EPS PCB, and the Batteries PCB. All the EPS2 project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/eps2) under its respective licenses.

<br><br>

<a href="https://github.com/spacelab-ufsc/battery-module-4c/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/battery-module-4c" />
</a>

## BATC4 - Battery Module 4 cells

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-4c/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/battery-module-4c?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-4c/commits/master">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/battery-module-4c?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-4c/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/battery-module-4c?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/battery-module-4c">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/battery-module-4c/blob/master/images/bat2-pcb-bottom.png">
</a>

The battery module is a separeted board from the EPS in order to accommodate 4 lithium-ion cells. Besides the cells, the board has connectors for interfacing signals and power lines with the EPS module, 2 power resistors to operate as heaters to maintain the cells temperature during eclipse periods, and 4 temperature sensors. The batteries used are the ICR18650-30B lithium-ion cells, which are connected in series and parallel to supply the required voltage and current. Each cell is fixed with 18650 metal holders and between the pairs there is the power resistor attached with a thermal element in the middle. Also, a mechanical mount is placed over the batteries and screwed to the board, providing better stress resistance. All the BATC4 project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/battery-module-4c) under its respective licenses.

<br><br>

<a href="https://github.com/spacelab-ufsc/interface-board/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/interface-board" />
</a>

## IIP - Interstage Interface Panels

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/interface-board/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/interface-board?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/interface-board/commits/master">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/interface-board?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/interface-board/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/interface-board?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/interface-board">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/interface-board/blob/master/doc/figures/iip_fullset.PNG">
</a>

Interstage Interface Panels (IIP) are vertical mounted PCBs designed to give external access to the modules inside of a 2U or 3U CubeSat during final assembly, integration and testing. IIP is composed by 3 different boards, the complete set allows for the nanosatellite to be charged, programed and debugged. All the IIP project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/interface-board) under its respective licenses.

<br><br>




## Partners

#### Space Technology Research Laboratory (SpaceLab)

<p float="left">
  	<a href="https://spacelab.ufsc.br/">
  		<img src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/spacelab-logo-full-color-rgb-1000px%4072ppi.png" width="37%" />
  	</a>
</p>

#### Federal University of Santa Catarina (UFSC)

<p float="left">
    <a href="https://ufsc.br/">
        <img src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/ufsc-logo.png" width="30%" />
    </a>
</p>

#### Brazilian Space Agency (AEB)

<p float="left">
  	<a href="https://www.gov.br/aeb/pt-br">
  		<img src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/aeb-logo.png" width="27%" />
  	</a>
</p>

#### Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq)

<p float="left">
  	<a href="https://www.gov.br/aeb/pt-br">
  		<img src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/cnpq-logo.png" width="27%" />
  	</a>
</p>

## Licenses

The SpaceLab follows a strong open-source approach in order to encourage and promote knowledge. Then, refer to the LICENSE file in the GitHub page for each repository. This mission uses different open-source licenses accordingly to projects needs and restrictions. It is used GNU General Public License v3.0 for firmware sources, CERN Open Hardware License v2.0 for hardware files, and CC BY-SA 4.0 for the documentation. Some third-part files and libraries are subjected to their specific terms and licenses. Please, double check licenses and third-part components used with other licenses, since restrictions might apply.

## Notes

This repository includes the sources of the main documentation. In order to edit/compile/generate, check the following:  

#### Dependencies

* ```latexmk```
* ```texlive-epstopdf```

#### Generating the PDF file

```
make
```




<!--
TBD






<br><br>

<a href="https://github.com/spacelab-ufsc/pc104-adapter/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/pc104-adapter" />
</a>

## PC104-ADPT - PC-104 Adapter

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/pc104-adapter/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/pc104-adapter?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/pc104-adapter/commits/master">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/pc104-adapter?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/pc104-adapter/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/pc104-adapter?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/pc104-adapter">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/pc104-adapter/blob/master/doc/figures/pc104-adapter.png">
</a>

The PC-104 Adapter is a set of two boards that allow the connection between two separated stacks of PC-104 boards using PicoBlade cables. All the 104 pins of the PC-104 connector are connected through the cables. The Top Board has eight PicoBlade connectors (13 pins version) on the bottom side and a PC-104 connector (female) on the top side. The Bottom Board has eight PicoBlade connectors (13 pins version) on the top side and a PC-104 connector (male) on the bottom side. All the PC104-ADPT project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/interface-board) under its respective licenses.

<br><br>



<br><br>

## Payload EDC - Environmental Data Collector Payload

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-under%20testing-yellow?style=for-the-badge">
	</a>
	<a href="">
		<img src="https://img.shields.io/badge/release-v1.1-blue?style=for-the-badge">
	</a>
</p>

<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/edc-pcb-top.png">

The Environmental Data Collector (EDC) is a CubeSat-compatible payload that decodes signals from Platform Transmitter Terminals (PTTs) belonging to the Brazilian Environmental Data Collection System and the Argos-2 system. The EDC is composed by an RF Front End and a Processing Unit. The processing unit is based on an SoC FPGA, which configures the external components at system initialization, processes the digital signal from the RF Front End and handles the communication with the On-Board Computer (OBC). 

<br><br>



<br><br>

<a href="https://github.com/spacelab-ufsc/flatsat-platform/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/flatsat-platform" />
</a>

## FlatSat - FlatSat Test Platform

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/flatsat-platform/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/flatsat-platform?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/flatsat-platform/commits/master">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/flatsat-platform?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/flatsat-platform/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/flatsat-platform?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/flatsat-platform">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/flatsat-platform/blob/master/doc/figures/flatsat_top_image.PNG">
</a>

The SpaceLab FlatSat Platform is a testbed for cubesat pcb modules. FlatSats enable easier, faster and secure method for testing subsystens indenpently or integrated in a flat design before going to assembly on a cubesat standard. The PCB can support up to 7 modules, all PC104 pins are interligated with each respective counterpart to flexibilize its use, only the particularity connection between modules need to be be taken into account. All the PC104-ADPT project, source and documentation files are available freely on a [GitHub repository](https://github.com/spacelab-ufsc/flatsat-platform) under its respective licenses.

<br><br>




<br><br>

<a href="https://github.com/spacelab-ufsc/spacelab-decoder/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=spacelab-ufsc/spacelab-decoder" />
</a>

## SpaceLab-Decoder

<p align="left">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/spacelab-decoder/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/spacelab-decoder?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/spacelab-decoder/commits/main">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/spacelab-decoder?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/spacelab-decoder/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/spacelab-decoder?style=for-the-badge">
	</a>
</p>

<a href="https://github.com/spacelab-ufsc/spacelab-decoder">
<img align="right" width="25%" src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/main/figures/spacelab-decoder.png">
</a>

SpaceLab-Decoder is a software to decode audio records from the satellites of SpaceLab.

<br><br>




#### National Institute for Space Research - Northeast Regional Center (INPE-RN)

<p float="left">
  	<a href="http://www.inpe.br/crn/">
  		<img src="https://github.com/spacelab-ufsc/radio-occultation-doc/blob/master/figures/inpe-logo.png" width="23%" />
  	</a> 
</p>
-->
