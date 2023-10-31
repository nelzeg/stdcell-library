## Open-Source Standard Cell Design Methodology 

This repository contains the files of the project *Open-Source Standard Cell and I/O Cell Design*.  
This project was developed by the students **Jhon Pinto** and **Nelson Rodriguez** with the direction of professors **Sebastian Moya** and **Jaime Barrero** at the [**Industrial University of Santander**](https://uis.edu.co/en/)

> The detailed documentation of this project could be read [here](./CECIOCA_Paper.pdf).  

### Standard Cell Library  

> Student: **Nelson Rodriguez**    

Ten standard cells were designed and characterized using the [Sky130 PDK](https://skywater-pdk.readthedocs.io/en/main/) and are saved in the folder [standard-cells](./).
1. [INV](./01-inv/)
2. [BUFF](./02-buff/)
3. [NAND2](./03-nand2/)
4. [NOR2](./04-nor2/)
5. [AOI21](./06-oai21/)
6. [OAI21](./06-oai21/)
7. [AOI22](./07-aoi22/)
8. [OAI22](./08-oai22/)
9. [AOI211](./09-aoi211/)
10. [OAI211](./10-oai211/)

Each cell folder contains the following files:
- Layout (`.mag`)
- LEF (`.lef`)
- Extracted Spice model (`.spice`)
- LIB (`.lib`)
- Timing data (`.txt`)

It was developed a set of scripts during the design process and for the cell characterization:  
1. [DSCC](./scripts/dscc/) : Digital Standard Cell Characterization tool.
2. [Fo4](./scripts/fo4/) : Data and post-processing script for the Fo4 testbench.
3. [Grid Template](./scripts/grid-template/) : Script to create custom height grids for layout implementation.
4. [Inverter Chain](./scripts/inverter-chain/) : Data and post-processing scripts for the inverter chain testbench.
5. [Results](./scripts/results/) : Testbench for timing measurements of the inverter designed with the optimal widths obtained.    

The whole repository could be found [here](https://github.com/ceciocauis/ceciocauis)