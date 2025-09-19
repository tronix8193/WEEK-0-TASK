# WEEK-0-TASK
# Installing Yosys, Icarus Verilog, and GTKWave on Ubuntu/WSL

This repo documents the steps I followed to set up a **Verilog development environment** on Ubuntu (WSL) on Windows.

# VLSI Setup Automation
Automating installation and setup of Yosys, Icarus Verilog and GTKWave.
This assigned task helped me quickly set up Yosys, Icarus Verilog and GTKWave on my system.
## Features
- Download and install Yosys (Open source Verilog synthesis tool)
- Download and install Icarus Verilog (Verilog simulator)
- Download and install GTKWave (Waveform viewer)
- Verify installation
##  Environment
I already had Ubuntu on Windows, so I used that to download the three open sources (Yosys, gtkwave and iverilog). 
- **OS:** Ubuntu 22.04 LTS (WSL2 on Windows 11)
- **Shell:** bash
- **RAM:** 8 GB
  
## Installation Steps

### 1. Update Ubuntu
```bash
sudo apt update
sudo apt upgrade -y
```
### 2. Installation of Yosys
```bash
sudo apt install -y yosys
yosys -V
```

### 3. Installation of Icarus Verilog
```bash
sudo apt install -y iverilog
iverilog -V
```

### 4. Installation of GTKWave
```bash
sudo apt install -y gtkwave
gtkwave --version
```

### 5. Verification
After installing, I verified the installed versions, using the following commands:

```bash
yosys -V
iverilog -V
gtkwave --version
```
### And the outputs I got are :
- Yosys 0.9 (git sha1 ...).
- Icarus Verilog version 10.3 (stable).
- GTKWave Analyzer v3.3.103.

## My learnings so far:
- installation open-source EDA tools on Ubuntu (WSL)
- To check versions and verify installation
- Difference between VirtualBox approach and WSL approach



