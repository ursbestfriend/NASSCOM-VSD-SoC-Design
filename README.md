# NASSCOM-VSD-SoC-Design
VSD Workshop on **Digital SoC Design and Planning** using OPENLANE FLOW collaboration with **NASSCOM FutureSkills Prime**.
This GitHub repository serves as a comprehensive resource for the VSD Workshop.  
[DAY 1 Inception of open-source EDA, OpenLANE and Sky130 PDK](#D1)  
[DAY 2 Good floorplan vs bad floorplan and introduction to library cells](#D2)  

<a id="D1"></a>
## Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK   
  **SKY130 D1 SK1- How to talk to computers**   
 
***SKY L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPS***   

**QFN-48 Package:** This refers to an introduction to a specific type of integrated circuit (IC) package called a Quad Flat No-lead package with 48 electrical connections.  
**Chip:** A chip, also commonly called a microchip or integrated circuit (IC), is a miniaturized electronic circuit containing a large number of transistors, resistors, capacitors, and other electronic components all fabricated on a single piece of semiconductor material (usually silicon).  
**Pads:** Pads are the connection points on a chip's exterior that allow it to be electrically connected to a package or other circuit board. They are essentially landing zones for external signals.
**Core:** In the context of an SoC (System-on-Chip), the core refers to the central processing unit (CPU) or other primary functional unit of the chip. It's the heart of the processing power.  
**Die:** The die (or integrated circuit die) is the actual chip itself before it's packaged. It's a tiny square or rectangular piece of silicon containing the fabricated electronic circuitry.  
**IPS:** IPS refers to "Inches Per Square" which is a unit used to specify the density of components on a chip. A higher IPS indicates a more densely packed chip with more transistors or other components per unit area.  
![d1p1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ef8e9579-8c88-4273-b8d4-b74b2c039d2a)  

***SKY L2 - Introduction to RISC-V***  

***Your Brain (CISC):*** This is like a complex calculator with many buttons. It can do everything: addition, subtraction, multiplication, division, even trigonometry and statistics! But for simple addition, you might need multiple button presses (like adding several numbers together).  

***Your Calculator (RISC):*** This is a simpler calculator with just a few buttons: add, subtract, multiply, and divide. It can't do everything your brain can, but for basic tasks, it's much faster because each button performs a specific, simple function.  
RISC-V (pronounced "risk-five") is like the calculator in the computer world. It's a type of instruction set architecture (ISA) that focuses on keeping things simple.  

***RISC (Reduced Instruction Set Computing):*** This means the processor focuses on a small set of basic instructions, similar to the calculator buttons.  
***Instruction Set Architecture (ISA):*** This is a language the processor understands, telling it what to do with data.   

***Benefits of RISC-V:***    
***Simpler Design:*** Less complex instructions make RISC-V processors potentially smaller and more energy-efficient.  
***Flexibility:*** The basic design allows for customization to fit different needs, similar to having different calculators for scientific or financial purposes.  
***Open Source:*** Anyone can design and build RISC-V processors, fostering innovation and collaboration.  
RISC-V is a relatively new architecture, but it's gaining popularity due to its flexibility and efficiency.   
![d1p2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e81cdb4d-fe3c-4696-8999-cae16bc8f4a1)  

***SKY L3 - From Software Applications to Hardware***    
Imagine writing instructions for a robot. That's what programmers do when they create software! But robots (and computers) only understand very specific commands. Here's the journey your code takes to become something the chip can understand:  
**Higher Level Language:** You write code in a language you understand, like Python or C++. This is easy for humans to read and write, but not for computers.    
**Compiler:** The compiler acts as a translator. It takes your higher-level code and converts it into assembly language, a lower-level language that's closer to what the machine understands.  
**Assembler:**  The assembler then takes the assembly language and translates it into machine code. This is a series of very specific instructions (0s and 1s) that the processor can directly execute.  
**Operating System (OS):**  The OS acts as a manager, preparing the machine code for execution. It allocates memory, handles input/output, and ensures everything runs smoothly.  
**Chip:** Finally, the machine code reaches the chip, specifically the Central Processing Unit (CPU). The CPU decodes the instructions and performs the actual operations like calculations or data manipulation.    
![d1p3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5b52eade-0a73-403c-95ee-2a9a6fea7112)  
### SKY130 D1 SK2 - SOC design and OpenLANE 
***SKY L1 - Introduction to all components of open-source digital ASIC design***  
***SKY L2 - Simplified RTL2GDS flow***  
***SKY L3 - Introduction to OpenLANE and Strive chipsets***  
***SKY L4 - Introduction to OpenLANE detailed ASIC design flow***  
### SKY130 DI SK3-Get familiar to open-source EDA tools  
***SKY L1 - OpenLANE Directory structure in detail***  
***SKY L2 - Design Preparation Step***  
***SKY L3 - Review files after design prep and run synthesis***  
***SKY L4 - OpenLANE Project Git Link Description***  
***SKY L5 - Steps to characterize synthesis results***
<a id="Topic"></a> 
### OPENLANE ASIC FLOW | Transform your RTL code to GDSII 
![42](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e3e50092-f4ae-400e-9a25-885c6811a433)

### Follow the below commands in sequence to generate RESULTS AND REPORTS:
![tp1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/804d88cc-faa2-4b93-8071-39e02b657d65)
  
For More details:  [CLICK HERE](https://github.com/The-OpenROAD-Project/OpenLane/blob/master/docs/source/reference/interactive_mode.md)

### Below are the steps to generate results and reports in the interactive mode.
#### STEP 1.	Open Terminal *(Shortcut – CLT + ALT + T)*
![tp2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/732b66c9-d64f-44bc-95ba-7752a2fe646a)
For more information on the Terminal command : [CLICK HERE](https://help.ubuntu.com/community/UsingTheTerminal)
#### STEP 2.	Follow the PATH – using the command: *cd  <Folder_Name>*
![tp3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/8024d2d4-413b-4c0a-a981-8a3321207e2d)
#### STEP 3.	Go to Design Name: *picorv32a*
 ![tp4](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4bebafdc-486c-4507-b802-2005c0bcd256)
#### STEP 4.	After the Entire FLOW – *runs* Folder will be created.
![tp5](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/edf5ca4c-c24d-42f0-bafb-7c6e1310ed49)
#### STEP 5.	The date when you completed the flow that *DATE FOLDER* will be there; Here *14-03_13-56*
![tp6](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/fedc1202-b676-4dcf-b43c-422cd0b68fd0)
#### STEP 6.	You will get the *results* and *reports* folder inside.
 ![tp7a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/2e8acf39-2ffb-4ea6-97cb-b92c668d12be)
![tp7b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ce299c8f-0d98-4864-807f-1c192b49a029)
![tp7c](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/558ee9f7-31d3-4565-a310-5fc569225401)
#### STEP 7.	RESULTs Folder Path inside Ubuntu
![tp8](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/46e60376-12e5-4b6c-b62c-3cb8f7fe131b)
#### STEP 8.	RESULT of SYNTHESIS, CTS, ROUTING, PLACEMENT, MAGIC
![Ttp12](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/91858e16-9608-4a9c-942c-a1d74e30f7e1)
![tp11](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/181fa85d-c489-4af0-8691-9d87e9a0cd36)
![tp10](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/506a4eeb-ae9d-42e6-b7ec-6ad7c261f4cb)
![tp9](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9ae4ce85-9ac9-4881-bc33-1e4cc0c50127)    
### Flop Ratio Count
![flop_ratio](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4d52af77-d347-4295-b463-b030546982c0)

<a id="D2"></a>
## DAY 2 -  Good floorplan vs bad floorplan and introduction to library cells  
  ### SKY130 D2 SK1 - Chip Floor planning considerations  

### SKY L1 -Utilization factor and aspect ratio 
**Utilization Factor (UF):**
Imagine the chip layout as a rectangular plot of land. The utilization factor represents the portion of this land that you'll use to build your house (the functional circuitry).  
Mathematically, UF = Area used for logic cells / Total core area  
***Area used for logic cells:*** This includes standard cells, memory blocks, and other functional components.  
***Total core area:*** This is the entire designated area within the chip for placing these components.   
![P16](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/18800d1e-228e-4e2c-93f1-32638d4b31e0)  
### SKY L2 -Concept of pre-placed cells    
#### What are Pre-Placed Cells? 
Pre-placed cells are critical components in a chip design whose placement is fixed before the automated layout process begins.They are typically placed during the "floorplan" stage, which defines the overall layout of the chip.Once placed, these cells stay put while other components (logic cells) are positioned and connected during the "placement and routing" stage.    
#### Why Pre-Place Cells?  
***Performance:*** Certain cells impact the chip's speed and reliability. Clock buffers, for example, need to be strategically placed to ensure signals reach all parts of the chip on time. Moving them later could disrupt these timing constraints.  
***Power Delivery:*** Power and ground connections are vital, and some cells, like decoupling capacitors, help maintain stable voltage levels. Pre-placing them near power-hungry areas ensures efficient power delivery.
***Physical Constraints:*** Some cells, like large memory blocks or analog circuits, have specific size and shape requirements. Pre-placing them helps avoid conflicts during the layout process.  
#### Examples of Pre-Placed Cells:
***Clock Buffers and Clock Muxes:*** These cells distribute and synchronize clock signals throughout the chip. Their precise location is crucial for timing performance.  
***Memory Blocks (RAM, ROM):*** These are often large and have specific layout requirements. Pre-placing them ensures they fit well and connect efficiently.  
***I/O Pads:*** These connect the chip to external components. Their placement around the chip's periphery is predefined.  
***Power Planning Cells:*** Decoupling capacitors, well taps, and power/ground rails are pre-placed to optimize power delivery.  
***Analog Circuits:*** These may have unique layout constraints that necessitate pre-placement.  
#### Benefits of Pre-Placed Cells:
***Predictable Performance:*** By fixing the location of critical cells, designers can ensure predictable timing and power behaviour.
***Faster Layout:*** The automated placement and routing tools don't waste time trying to fit these cells in, speeding up the layout process.
***Design Integrity:*** Pre-placement prevents accidental movement of crucial cells, maintaining the design's integrity.  
![P36](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/339e3e3b-90a7-4779-b443-a84285fc99b3)

#### Imagine a Bakery as a Chip:  
Think of the chip layout as a bakery floor. Pre-placed cells are like the ovens and large mixing bowls – they have specific locations due to their size and function. The remaining space is where the baker (automated layout tools) arranges the mixing stations, dough prep areas, and other equipment (logic cells) for an efficient workflow.    

### SKY L3 - De-coupling capacitors  
Decoupling capacitors, also sometimes called bypass capacitors, are tiny workhorses in the world of electronics. Their job is to maintain a steady voltage supply for integrated circuits (ICs) and other components on a circuit board.  
***Power Delivery Smoothing:***   
Imagine the power supply as a water pipe. Ideally, you want a constant flow of water pressure for your devices. However, real-world power supplies can have tiny fluctuations or ripples in voltage.  
***Capacitor as a Reservoir:***   
Decoupling capacitors act like miniature reservoirs. When the voltage dips slightly, the capacitor releases some of the stored energy to compensate, keeping the voltage level stable for the IC. Conversely, if there's a brief voltage spike, the capacitor absorbs the excess energy, preventing damage to the IC.    
***Noise Reduction:*** Electronic circuits can generate electrical noise that can interfere with the proper functioning of ICs. Decoupling capacitors act like filters, shunting this high-frequency noise to ground, preventing it from affecting the IC's operation.  
![P34](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/48ce3231-6131-46e3-9b39-8afe1bb86a7f)  

These capacitors are typically placed very close to the power pins of ICs. This minimizes the distance that current needs to travel, further enhancing their effectiveness.  
### SKY L4-  Power planning   
Power planning in chips ensures all parts get a steady voltage. It's like building a power grid on a tiny scale, with rings and grids delivering clean power and preventing glitches.  

![P46](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/294d3468-2209-4c36-a720-ef252e56ca9e)  
### SKY L5 - Pin placement and logical cell placement blockage   
Pin placement in chip design is a crucial step that impacts a chip's performance, manufacturability, and overall functionality. It involves strategically positioning the input/output (I/O) pins that connect the chip to the external world.Pin placement is a collaborative effort between chip designers, power planning engineers, and layout specialists. They work together to find the optimal balance between functionality, performance, and manufacturability.  
![P56](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/1e4a4b8e-1f14-403e-8e0c-969dafa73267)  
### SKY L6 - Steps to run floorplan using OpenLANE after Modification  
### SKY L7 - Review floorplan files and steps to view floorplan  
#### Step 1 Update the config.tcl of picorv32a Folder
 ![P64_parameterSet](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/18d05754-fdb3-425a-93be-a0bf6b2eaa29)
#### Step 2 RUN docker +  prep -design  +  synthesis  + floorplan

![P66_runDocker_floorplan](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/7989eba5-6056-4c01-b03f-434b8dedec18)  
![P66_runDocker_synthesis](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e0f89348-fdcf-4854-925e-9bd98666044a)  
![P67_sky130A_tcl](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9e4de8c4-3b10-43d4-a88d-83bb5e73f5d8)  
![P71_updated2_BasedPripority_sky130](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/0b38bb64-48aa-434a-b730-f4a16ad1fa81)  
![P71_updated_BasedPripority_sky130](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a164157c-4a95-493d-b560-2660940c14d0)  

### SKY L8 - Review floorplan layout in Magic (steps in Descending Order in Image) 
***magic -T /Home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def***  

![P73_magicLayout_S_V](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/86eb36b7-ec95-40ea-8eff-e4de8bca5018)  
![P73_magicLayout_mouse](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4e54046a-4208-4761-aae1-9c5daba9cc0c)  
![P73_A_different_thanVideo2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/85b58f18-46f7-46aa-8586-33db368afb0b)  
![P73_A_different_thanVideo](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/73acac80-af45-4358-b1f1-562a2cf3995b)  
![P72_magicTech_mergeLef_cell-tech](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e68a5463-a97f-4501-bce5-cae92e2c1889)  
![P72_defmagic_open](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/fa4f837d-3a58-4479-a348-b564f9e33c3a)  
![P72_defmagic_merging](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c1b0f241-126d-4807-b056-7e1542abbd5b)  
![P72_def_floorplan2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3dd0c00a-6e2c-4e47-989f-c96f32dd7c2d)  
![P72_def_floorplan](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/aedcebe2-3166-494a-8e44-0a90f2dc2b9e)  
![P72_def_Area](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3476cb31-d15e-4557-8cd5-fda8221c96f2)  
![P71_updated2_BasedPripority_sky130](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ca08790a-f0cb-42ff-bfd3-00c47aab4cd0)    
### SKY130 D2 SK2 - Library Binding and Placement  
#### SKY L1 - Netlist binding and initial place design  
#### SKY L2 - Optimize placement using estimated wire length and capacitance  
#### SKY L3 - Final placement optimization  
Imagine designing a house. The netlist is like the architectural plan, specifying the rooms and their connections. Library binding is selecting pre-fabricated modules like kitchens, bathrooms, etc., based on the plan. Finally, initial place design is roughly arranging these modules on the building plot.These steps lay the groundwork for the physical design of the chip. They ensure the logic functionality is translated into real hardware components and provide a starting point for optimizing the chip's performance and area usage.  
**Netlist Binding:**  
A netlist is a textual representation of your circuit. It describes the connections between different logic elements like gates, flip-flops, etc. Think of it as a blueprint for the logic functionality.  
![P74_D2_sk2_L1_1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3f74102a-dfa1-428e-82ad-48581f8872e0)  

**Library binding** involves mapping the generic elements in the netlist to actual physical components (cells) from a pre-designed library. These libraries are provided by the chip manufacturer and contain information about the functionality, size, and electrical characteristics of each cell.  
**Netlist binding** the design tool searches the library for cells that match the functionality described in the netlist.It essentially replaces the generic elements with their specific hardware counterparts.   
![P74_D2_sk2_L1_7](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/723d5b38-ea66-4237-9851-f4cb37d13895)  

**Initial Place Design:**  
After binding the netlist to library cells, the next step is to figure out where to physically place these cells on the chip. This initial placement is crucial because it can significantly impact factors like performance, power consumption, and routability (ease of connecting cells with wires).  
Initial place design involves roughly placing the cells on the chip layout. This placement might not be optimal at this stage, but it serves as a starting point for further refinement in later design stages.  
![P74_D2_sk2_L1_15](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a87f22b6-dee0-41bb-be24-28d46089558f)    
#### SKY L4 - Need for libraries and characterization  
#### SKY L5 - Congestion aware placement using RePlAce  
**Libraries:**
Like Lego sets with pre-built components (doors, windows), IC design uses libraries of pre-designed and tested circuit elements called "cells" (gates, flip-flops, etc.).
These cells are like building blocks that guarantee functionality and save time compared to designing each element from scratch.
**Characterization:**  
Each Lego brick has a specific size and how it connects. Similarly, cells in libraries need characterization. This involves simulating and understanding how each cell performs under different conditions (speed, power usage).Characterization creates a "model" for each cell, which design tools use to predict how the entire circuit will behave. This ensures the final chip functions correctly and meets performance targets. In short, libraries provide pre-built, reliable components, and characterization tells us exactly how these components behave, allowing designers to efficiently build complex and functional ICs.  
![P74_D2_sk3_L1_6](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/217b3003-8aca-4006-967c-c7bdc620d497)   
![P74_D2_sk3_L3_15](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/387f7c6e-4403-4d63-9b32-d253c58d0319)  
### SKY130 D2 SK3 - Cell design and characterization flows 
#### SKY L1 - Inputs for cell design flow   
#### SKY L2 - Circuit design step   
#### SKY L3 - Layout design step   
#### SKY L4 - Typical characterization flow  
 ##### Cell Design Flow:
**Inputs:**
___**Functionality**: What logic operation should the cell perform (e.g., AND gate, inverter)?  
___**Process Design Kit (PDK):** A set of rules and specifications provided by the chip manufacturer, defining how transistors and other elements can be built on the chip.  
**Circuit Design Step:**  
___**Schematic capture:** Using a tool, designers create a symbolic representation of the cell's circuit with transistors and connections.  
___**Simulation:** The circuit is simulated to verify its functionality under different conditions.    
**Layout Design Step:**  
__**Place and Route (PnR):** The transistors and connections are arranged on the chip layout, ensuring proper spacing and connections between them.  
__**Design Rule Check (DRC):** Ensures the layout meets the PDK rules to guarantee manufacturability.  
__**Layout Versus Schematic (LVS):** Verifies the final layout accurately reflects the original schematic.    
![P74_D2_sk3_L2_10](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/63855f07-451e-4f9c-bc1e-c569490a04d2)  
![P74_D2_sk3_L2_13](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/72ed3cea-6c9e-4d98-9b69-7f2c00420a24)  
![P74_D2_sk3_L2_17](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9fedbbdf-47f1-477e-8f91-819d4ecf42f9)  
![P74_D2_sk3_L3_16](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/49843f62-51b5-4e35-baae-bd4d2f9f2d00)

### SKY130 D2 SK4 - General timing characterization parameters  
#### SKY L1 - Timing threshold definitions  
#### SKY L2 - Propagation delay and transition time  
 Designing a chip is like building a miniature race track for electrical signals. Cell characterization is key to understanding how fast these signals travel.  Just like on a race track, we define parameters to measure performance. Propagation delay (tpd) is the time it takes a signal to cross the finish line (output) after the starting flag (input) changes. Transition time (ttr) is how long it takes the signal to accelerate between voltage levels.  For a successful race, the driver needs a good head start. Similarly, setup time (tsu) defines the minimum time the input signal needs to be stable before the go signal (clock edge) arrives for the output to be valid. Hold time (th) is like the driver needing to stay put for a moment after the start to ensure a smooth transition.  Timing thresholds define the voltage levels that signify valid 0s and 1s on the track. By characterizing cells with these parameters, designers can ensure signals travel quickly and arrive at the right time, keeping your electronic device running like a well-oiled racing machine!  

![P74_D2_sk4_L1_3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/7a75c81b-9bde-4085-9962-0413d7423e0c)  
![P74_D2_sk4_L2_2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/967e6c74-5e26-42fa-81e2-74a98786dc01)  
![P74_D2_sk4_L2_5](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c7ab2cc5-1450-4ccb-82e2-6fca7360bba9)  
![P74_D2_sk4_L2_7](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/cc3fc96c-eea7-4411-983b-667421a54be8)  
![P74_D2_sk4_L2_14](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9b6ded2b-aca6-43fd-9137-9f553aadbc21)  
