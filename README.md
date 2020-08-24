# Donut math
![Build](https://github.com/Ryzee119/donut/workflows/Build/badge.svg)  
Code to generate a rotating ascii torus or 'donut'.  
Credit to https://www.a1k0n.net/2011/07/20/donut-math.html


## Build (Linux/Windows)
* Requires `gcc` and `make`
* Build with `make`

## Build (OG Xbox)
To build for OG Xbox setup and install [NXDK](https://github.com/XboxDev/nxdk)
```
cd~
export NXDK_DIR=/path/to/nxdk
git clone https://github.com/Ryzee119/donut.git
cd donut
make -f Makefile.nxdk
```
