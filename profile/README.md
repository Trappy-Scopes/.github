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

1. [`scope_cli`](https://github.com/Trappy-Scopes/scope-cli) : Control layer software for <u>controlling</u> Trappy-Scopes microscopy system.
2. [`pico_firmware`](https://github.com/Trappy-Scopes/pico_firmware): Common firmware for all Raspberry Pi Pico W / micropython devices.
3. [`trappyframe`](https://github.com/Trappy-Scopes/trappyframe): 3D printing files for the Trappy-Scopes frame.
4. [`electronics`](https://github.com/Trappy-Scopes/electronics) : Circuit diagrams and database of custom electronic assemblies and circuit boards.
5. [`raspberry_shrub`](https://github.com/Trappy-Scopes/raspberry_shrub) : Configure Raspberry Pis for multiplexed operation.
7. `assembly_peripherals` : Repository of 3D models of Trappy-Scopes assembly parts.
8. [`trackyscope`](https://github.com/Trappy-Scopes/trackyscope) : Tracking pipeline and postprocessing code.
9.  [`microfluidics`](https://github.com/Trappy-Scopes/microfluidics) : Microfluidics design files and renderings.

### Machine specific repositories

1. `pico_incubator` : Firmware for RPi Pico W based cell incubator.
2. `pico_photometer`: Firmware for RPi Pico W based 10-channel spectra-photometer.
3. `current_controller`: Firmware for RPi Pico W and LT3092 based current controllers for illumination.
4. `syringe_pump`: Firmware for RPi Pico W based multi-channel peristatic pumps.



### Lab Management / Experiment Repositories

1. [`lab`](https://github.com/Trappy-Scopes/lab)) : Repository for stocks, cell_culture logs, etc.
2. [`protocols`](https://github.com/Trappy-Scopes/protocols) : Repository of lab protocols.
3. `cell_counts` : Repository database for cell counting and automatic plotting of growth curves.
4. `notes `: Repository to sync notes, pdf, other stuff.
5. `scratch `: Repository for sharing jupyter notebooks that are not cleaned, etc.
6. `experiments_yb` : Analysis notebooks for YB.



---

## Main control layer repositories for devices

1. `mainframe`: Network admin node - two Raspberry Pi 4B SoC devices.
2. `cluster_head`: Remote Access control tool.
3. `scope-cli`: Trappy-Scopes based on Raspberry Pi 4B SoC.
4. `pico_firmware`: Firmware for Raspberry Pi pico W MCUs.

