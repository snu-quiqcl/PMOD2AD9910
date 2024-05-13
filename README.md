# PMOD2AD9910
## Overview
<p align="center">
<img width="1004" alt="image" src="https://github.com/snu-quiqcl/PMOD2AD9910/assets/49219392/54bfe1d6-3c55-4cc4-abbf-41ee24ff67e4">
</p>

This PCB board converts the ArtyS7 PMOD connectors to QuIQCL AD9910 IDC connectors. SMA connectors are included for external profile input. External profile pins are provided because the AD9910's RAM mode requires a profile pin signal at set time, although actual experiments are conducted with an external FPGA (e.g., Sequencer). External profile signals are multiplexed within the ArtyS7.
