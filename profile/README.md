# Trappy-Scopes



Trappy-Scopes is a bespoke parallel microscopy system developed at the **Living Physics Laboratory**, situated at the *Instituto Gulbenkian de Ciência (IGC), Lisbon*.

```goat
  *     ████████╗    ██████╗      █████╗     ██████╗     ██████╗     ██╗   ██╗
  _     ╚══██╔══╝    ██╔══██╗    ██╔══██╗    ██╔══██╗    ██╔══██╗    ╚██╗ ██╔╝
 | |       ██║       ██████╔╝    ███████║    ██████╔╝    ██████╔╝     ╚████╔╝ 
 | |       ██║       ██╔══██╗    ██╔══██║    ██╔═══╝     ██╔═══╝       ╚██╔╝  
 |_|       ██║       ██║  ██║    ██║  ██║    ██║         ██║            ██║   
 |_|       ╚═╝       ╚═╝  ╚═╝    ╚═╝  ╚═╝    ╚═╝         ╚═╝            ╚═╝   
_____                                                                         
-----   ███████╗     ██████╗     ██████╗     ██████╗     ███████╗    ███████╗ 
 .^.    ██╔════╝    ██╔════╝    ██╔═══██╗    ██╔══██╗    ██╔════╝    ██╔════╝ 
 | |    ███████╗    ██║         ██║   ██║    ██████╔╝    █████╗      ███████╗ 
 ---    ╚════██║    ██║         ██║   ██║    ██╔═══╝     ██╔══╝      ╚════██║ 
        ███████║    ╚██████╗    ╚██████╔╝    ██║         ███████╗    ███████║ 
 ===    ╚══════╝     ╚═════╝     ╚═════╝     ╚═╝         ╚══════╝    ╚══════╝
```



## Repositories at a glance

### Canonical repositiries

1. `scope_cli` : Control layer software for <u>controlling</u> Trappy-Scopes microscopy system.
2. `cluster_head` : Control layer software for <u>multiplexing microscopes</u>.
3. `pico_firmware`: Common firmware for all Raspberry Pi Pico W devices.
4. `rip_config` : Configuration software for all Raspberry Pi 4B SoC devices.
5. `electronics` : Circuit diagrams and database of custom electronic assemblies and circuit boards.
6. `assembly_peripherals` : Repository of 3D models of Trappy-Scopes assembly parts.
7. `analysis_pipeline` : Post-processing and analysis code. 
8.  `systems_overview` : For an arial view of the lab system. [TODO]

### Machine specific repositories

1. `pico_incubator` : Firmware for RPi Pico W based cell incubator.
2. `pico_photometer`: Firmware for RPi Pico W based 10-channel spectra-photometer.
3. `current_controller`: Firmware for RPi Pico W and LT3092 based current controllers for illumination.
4. `syringe_pump`: Firmware for RPi Pico W based multi-channel peristatic pumps.



### Lab Management / Experiment Repositories

1. `cell_counts` : Repository database for cell counting and automatic plotting of growth curves.
2. `lab` : Repository for stocks, cell_culture logs, and protocols.
3. `notes `: Repository to sync notes, pdf, other stuff.
4. `scratch `: Repository for sharing jupyter notebooks that are not cleaned, etc.
5. `experiments_yb` : Analysis notebooks for YB.



---