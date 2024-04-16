.
![Digital SoC Design and Planning using OPENLANE FLOW collaboration with NASSCOM FutureSkills Prime](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5129f3cc-ec01-414e-a7ce-6ab6cdaee3ea)

VSD Workshop on **Digital SoC Design and Planning** using OPENLANE FLOW collaboration with **NASSCOM FutureSkills Prime**.
This GitHub repository serves as a comprehensive resource for the VSD Workshop.  
[Topic 1 Inception of open-source EDA, OpenLANE and Sky130 PDK](#D1)  
[Topic 2 Good floorplan vs bad floorplan and introduction to library cells](#D2)  
[Topic 3 Design library cell using Magic Layout and ngspice characterization](#D3)  
[Topic 4 Pre-layout timing analysis and importance of good clock tree](#D4)  
[Topic 5 Final steps for RTL2GDS using tritonRoute and openSTA](#D5)  

<a id="D1"></a>
## Topic 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK   
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
![16](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/1a4de7a8-65be-49d4-aea4-81129cd75dcc)  

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
## Topic 2 -  Good floorplan vs bad floorplan and introduction to library cells  
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
**SKY L1 - Inputs for cell design flow**     
**SKY L2 - Circuit design step**     
**SKY L3 - Layout design step**     
**SKY L4 - Typical characterization flow**    
 #### Cell Design Flow:
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

<a id="D3"></a>
## Topic 3 Design library cell using Magic Layout and ngspice characterization  
### SKY130 03 SK1 - Labs for CMOS inverter ngspice simulations   

The CMOS inverter, short for Complementary Metal-Oxide-Semiconductor
inverter, is a fundamental building block in modern digital circuits. It
acts as a NOT gate, essentially flipping the input signal. But what
makes it special? Let\'s delve into its core components and the reasons
behind its dominance in chip design.

**The Power of Two: NMOS and PMOS Transistors**

A CMOS inverter consists of two types of transistors: the NMOS
(N-channel Metal-Oxide-Semiconductor) and the PMOS (P-channel
Metal-Oxide-Semiconductor). Imagine these transistors as switches
controlled by voltage. An NMOS conducts electricity effectively when a
positive voltage is applied to its gate relative to its source.
Conversely, a PMOS conducts when a negative voltage is applied to its
gate.

**The Logic Behind the Flip**

The beauty of the CMOS inverter lies in how these NMOS and PMOS
transistors are connected. Their gates are tied together, receiving the
same input voltage. Their drain terminals connect to a common point,
forming the output. Finally, the source of the NMOS connects to ground
(0V), while the source of the PMOS connects to the power supply (VDD).

When a low voltage (close to 0V) is applied as input, the NMOS conducts,
pulling the output down to ground (representing a logic 0). Conversely,
with a high voltage (close to VDD) as input, the PMOS conducts, pulling
the output up to VDD (representing a logic 1). This creates a clear
inversion of the input signal.

**Why CMOS Reigns Supreme**

-   **Low Power Consumption:** Unlike traditional inverters that
    constantly draw current, a CMOS inverter only consumes power during
    switching. When the output is stable (high or low), neither
    transistor conducts, minimizing power usage.

-   **High Noise Immunity:** The clear voltage levels (VDD and ground)
    used in CMOS make it resistant to noise and interference. This
    ensures reliable operation even in noisy environments.

-   **Scalability:** The CMOS design allows for miniaturization of
    transistors, enabling denser and more powerful integrated circuits.  
![d3_19](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/1403b99d-7bd7-4f1e-85ff-2e9f1c96e61d)  


#### SKY L0 - I0 placer revision     
 *Before FP IO set to value 1 = equidistance pin*  
![d3_3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/f65e8be4-bb85-4f5b-bfb8-59cb7bb5d65f)  
*After FP IO is set to value 2*   
![d3_6](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5b52b0bf-8c53-47d9-8436-3dd383b03cd8)    
![d3_8](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/57c3a592-0a69-49d5-b938-a2aee98e50b4)    
![d3_14](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/8b6f5807-ef39-42d2-b9dc-4f1636c86881)
![d3_11](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c38bdfbe-213b-4f91-bfd4-e4df531e4532)  
#### SKY L1- SPICE deck creation for CMOS inverter  
 ![d3_24](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/48c08790-5190-4f2a-94be-1a5ff764a44b)

#### SKY L2 - SPICE simulation lab for CMOS inverter  
 #### SKY L3 - Switching Threshold Vm ; Lab steps to git clone vsdstdcelldesign  
SPICE (Simulation Program with Integrated Circuit Emphasis) allows us to simulate the behaviour of electronic circuits. Here's a breakdown of creating a SPICE deck for a CMOS inverter: 

**1. Model Selection:**  
Include the model files for the NMOS and PMOS transistors used in the inverter. These files describe the electrical characteristics of the transistors based on a specific technology process. Common model formats include BSIM or PSPICE.  
**Example:**  

.model NMOS nmos_model LEVEL=4 (model parameters...)  
.model PMOS pmos_model LEVEL=4 (model parameters...)  
**2. Device Definition:**  

Define the NMOS and PMOS transistors with their sizes (width W and length L) and connection points.  
**Example:**

M1 out in gnd gnd NMOS W=1u L=0.5u  ; NMOS transistor  
M2 vdd in out vdd PMOS W=2u L=0.5u  ; PMOS transistor  
**3. Power Supply and Ground:**  

Define voltage sources for the power supply (VDD) and ground (GND).  
**Example:**

Vdd vdd 0 DC 5V  ; Power supply voltage source  
Vss gnd 0 DC 0V  ; Ground voltage source  
**4. Input Stimulus (Optional):**  

Include a voltage source or pulse source to define the input signal applied to the inverter.  
**Example:**  

Vin in 0 PULSE(0 5 0ns 1ns 1ns 10ns) ; Pulse input signal  
**5. Simulation Directives:**  

Specify the simulation type (e.g., transient analysis) and desired output (e.g., node voltages).  
**Example:**  

.tran 1ns 100ns  ; Transient analysis from 1ns to 100ns  
.print DC V(out) V(in) ; Print DC and transient voltages at output and input  
.plot DC V(out) V(in) ; Plot DC and transient transfer characteristics  
.end  
**OPEN CMOS INVERTER IN MAGIC**
![d3_192a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d03fdeda-026b-44cf-a6c3-eaf5ba125af4)
![d3_192_3b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4f28c06c-64cd-42f9-9b47-763d0e1c5842)  
![d3_sk1_l0_5_clone_inverInMagic](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a5b720a0-0bc2-4721-a056-71b70fe3690b)  
![d3_sk1_l0_5_clone_inverInMagic2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/1e3b6fe6-65ba-4c7e-8398-3905edbfb375)  
![d3_192_3a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/48cd7be5-d913-43e5-9695-d44e41aeb102)  
![d3_192_3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/77068cbc-fa82-472f-91ce-6027a6f79d31)  
![d3_sk1_l0_5_cloneVSDstdcelldesign](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d35f67b6-d8a4-422d-a5ef-c5972c729735)  
![d3_sk1_l0_5_cloneVSDstdcelldesign2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d898f4d1-8133-405b-a3d3-17851e3e2ae2)  
![d3_sk1_l0_6_spiceExtraction](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/048dd7d2-eb3d-43b7-ac78-b361b19e1b25)  
![d3_sk1_l0_6_spiceExtraction2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9bbf5823-5b5b-4798-9d44-c301714a2f0d)  
![d3_sk1_l0_6_spiceExtraction3_File](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/49fe0fc3-705e-4126-b27a-aa9f3cccd227)  
![d3_192_16](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/828d0a15-4411-4642-8ec0-1a2079dc4310)  
![d3_192_15](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/2dfadfff-5c2a-46f9-a2c7-485b3a06d3f2)  
![d3_192_18](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/73711053-dc07-45c0-b821-29c1f9c8903e)  
![d3_192_17](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c462b6ef-f635-4f7f-8665-711d7563731e)  

**Unit box Distance in Magic Layout**
![d3_192_22_0](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/34a87703-c733-4556-bb32-7ff8ef756d7a)

**Update the sky130_inv.spice File and OPEN in ngspice after installing** 


![d3_192_22a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/706d51fb-6fec-47d9-bcda-4be08de4795d)
![d3_192_22b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ddbab16c-b3d2-4434-b9d9-1eb6a76c0e13)
**Output of plot command on ngspice**
![d3_192_22c](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ae159160-f6a6-4ee7-8b6a-4c99861c0005)  

**RISE TIME , FALL TIME , Propagation Delay Calculation**  

![d3_192_22d](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/f5abf66f-ee84-41d1-96b0-f25f21cbdb3f)  

**RISE TIME (tr):**

-   Represents the time it takes for a signal to transition from 20% *( 3.3 * 0.2 = 0.66V)* to
    80% *( 3.3 * 0.8 = 2.64V)* of its steady-state value during a rising edge.
-   Here **RISE TIME (tr) =  2.23583e-09 -2.17734e-09 = 58.49 ps**

![d3_192_22g](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/47481231-7869-4211-b511-26966dc37cee)  
![d3_192_22f](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/446eb774-77f3-4b04-ac23-fab55114a0da)  


**FALL TIME (tf):**

-   Represents the time it takes for a signal to transition from 80% *( 3.3 * 0.8 = 2.64V)* to
    20% *( 3.3 * 0.2 = 0.66V)* of its steady-state value during a falling edge.  
-   Here **FALL TIME  =  **4.09538e-09 - 4.05279e-09 =4.259e-11 = 42.59 ps**
![d3_192_22h](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c5771356-293a-4c29-9f46-6c76f5471e2a)  


**Propagation Delay (tpd):**

-   Characterizes the time delay between a change in the input signal
    and the corresponding change in the output signal of a logic gate.
    It's often measured from the 50% *( 3.3 * 0.5 = 1.65V)* point of the input waveform to the
    50% *( 3.3 * 0.5 = 1.65V)* point of the output waveform.
- *RISE DELAY = Output_Rise(50%) - Input_Fall(50%) =2.20441e-09 - 2.15e-09 = 5.441e-11 = 54.41 ps*   
- *FALL DELAY = Output_Fall(50%) - Input_Rise(50%) =4.07785e-09 - 4.05054e-09 = 2.731e-11= 27.31 ps*
- 

**Measure Tool:**

-   Place cursors at the 20% *( 3.3 * 0.2 = 0.66V)*  and 80% *( 3.3 * 0.8 = 2.64V)* points for rise time and 80% and
    20% points for fall time on the output waveform.

-   The difference between the cursor positions (in time units) will
    provide the respective rise and fall times.



#### SKY L4 - Static and dynamic simulation of CMOS inverter   
*Static Simulation*  
![d3_47](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ffe85724-0c61-4012-81dc-65fb9ec87106)  
*Dynamic simulation*
![d3_61](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/33ebd80d-97ad-44e1-81d3-f05b53465bd3)  
![d3_61a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d290e5b0-ef7a-4283-a5b6-402b6bb3fd0f)  
![d3_64](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5183c24f-5c34-40ab-acf3-7c32b4cabe51)  

### SKY130 03 SK2 • Inception of Layout A CMOS fabrication process 
#### Create Active regions, Formation of N-well and P- well,Formation of gate terminal Lightly doped drain (LDD),formation SKY LS- Source A, A- drain formation,Local interconnect formation,Higher level metal formation,Lab introduction to Sky130 basic layers layout and LEF using inverter,Lab steps to create std cell layout and extract spice netlist   

**Substrate Preparation:**  

1.  **Silicon Wafer Cleaning:** Remove impurities from the silicon wafer
    surface.

2.  **Thermal Oxidation:** Grow a thin layer of silicon dioxide (SiO2)
    on the wafer for isolation and gate oxide.  

**Well and Active Area Formation:**

3.  **Well Implantation:** Implant dopant ions (Boron for p-well) to
    create a p-type region for the PMOS transistor.

4.  **Well Drive-in:** Diffuse the dopant ions deeper for better
    electrical characteristics.

5.  **Shallow Trench Isolation (STI):** Create trenches around active
    areas to isolate transistors electrically.  

**Gate Stack Formation:**  

6.  **Polysilicon Deposition:** Deposit a thin layer of polysilicon for
    transistor gates.

7.  **Polysilicon Patterning:** Define the gate patterns using
    photolithography and etching.  

**Doping and Channel Formation:**  

8.  **NMOS Threshold Adjust Implant:** Implant dopant ions (Arsenic or
    Phosphorus) to adjust the threshold voltage of the NMOS transistor.

9.  **PMOS Channel Implant:** Implant dopant ions (Boron) to create the
    channel region of the PMOS transistor.

10. **Channel Annealing:** Activate the dopant ions implanted in steps 8
    and 9.  

**Source/Drain Formation:**  

11. **Shallow Source/Drain Implant (NMOS):** Implant dopant ions
    (Arsenic or Phosphorus) to create the source and drain regions of
    the NMOS transistor.

12. **Shallow Source/Drain Implant (PMOS):** Implant dopant ions (Boron)
    to create the source and drain regions of the PMOS transistor.

13. **S/D Extension Implant (Optional):** Implant additional dopant ions
    to reduce source/drain resistance.  

**Contact and Metallization:**  

14. **Contact Hole Etching:** Etch holes through the gate oxide to
    connect gates to source/drain regions.

15. **Metal Deposition:** Deposit metal layers (e.g., aluminum) for
    interconnects and transistor connections.

16. **Metal Patterning:** Define metal patterns using photolithography
    and etching.

 ![d3_73](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/636900bb-d9e1-4c14-a7b3-71eb5b0d68a6)  
![d3_78](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/f6cd2843-20dd-4f54-864d-3c45550e3330)  
![d3_99](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/228801fe-97aa-464d-a672-d66610b4b0d0)  
![d3_150](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/8968a2b4-d240-4533-bbf0-139898aab983)  
![d3_156](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/30d3fb53-efbf-4c25-8b6a-5a0ee4b37bd2)   
![d3_187](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a2d99fde-10af-47da-8bd5-68f41dd0cab8)
![d3_190](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/0cb6bc82-df86-4b75-bddf-87191cc55f54)  

### SKY130 03 SK3 - Sky130 Tech File Labs  
####  Lab steps to create final SPICE deck using Sky130 tech, Lab steps to characterize inverter using sky130 model files, Lab introduction to Magic tool options and DRC rules, Lab introduction to Sky130 pdk's and steps to download labs,Lab introduction to Magic and steps to load Sky130 tech-rules

-   **Lab steps to create final SPICE deck using Sky130 tech:**

-   Define circuit schematic with inverter components.

-   Include Sky130 model file references for transistors.

-   Set simulation parameters (voltage sources, sweep ranges).

-   Verify netlist generation and format for SPICE simulation tools.

-   **Lab steps to characterize inverter using Sky130 model files:**

-   Run SPICE simulations of the inverter circuit.

-   Analyze output characteristics (DC transfer function, transient
    response).

-   Extract key inverter parameters (noise margin, propagation delay).

-   Compare results with theoretical expectations and model
    specifications.  
 
-   **Lab introduction to Magic tool options and DRC rules:**

-   Explore Magic user interface and basic drawing functionalities.

-   Learn about design rule checking (DRC) for layout verification.

-   Understand different DRC categories (spacing, width, well
    placement).

-   Utilize DRC features within Magic to identify and fix layout errors.

-   Understand the concept of Process Design Kits (PDKs).

-   Explore Sky130 PDK content (technology rules, model files, layout
    examples).




-   **Lab introduction to Magic and steps to load Sky130 tech-rules:**

-   Launch Magic layout editor software.

-   Load Sky130 PDK technology file containing design rules.

-   Set up drawing layers and styles according to PDK specifications.

-   Familiarize with basic layout editing commands in Magic.

**Introduction of Magic Layout Tool and Lab Exercises for Magic DRC**  
Magic is a tool for designing the layout of very-large-scale integration
(VLSI) integrated circuits (ICs). In other words, it\'s used to create
the blueprints for complex microchips.

**Origin:** Developed at UC Berkeley in the 1980s by John Ousterhout.

**Popularity:**

-   Open-source license: This allows for free access and modification,
    making it popular with universities and small companies.

-   Customization: The open-source nature allows engineers to add
    features and keep pace with evolving chip fabrication techniques.

-   Ease of use: Many find it to be a user-friendly tool for circuit
    layout, even if they use commercial tools for final designs.
 **Download lab File from http://opencircuitdesign.com/open_pdks/archive/drc_tests.tgz**
![d3_192_44b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/7ac29d5d-145e-4fe2-bd04-c8a001043ede)  
![d3_192_44a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/f7370f43-1c42-4b70-895c-61135b110f6f)  
**OPEN DESIGN IN MAGIC TO CHECK DRC error and SOLVE**
![d3_192_44c](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/0ba2c002-f56f-4fd1-aff1-eb7226ab5988)  
![d3_192_44d](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/1b5e61fb-692e-441e-82bc-eab694d4f9ed)  
![d3_192_44e](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/42a3f38b-e89f-4195-b168-b3374a253b41)  
*DRC Error in poly.mag*  
![d3_192_44e](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4241c40e-bf44-4b36-82a1-d0fbe545e0ea)  
*Online Reference for  DRC Rule of skywater 130 PDK: https://skywater-pdk.readthedocs.io/en/main/rules/periphery.html#poly*
![d3_192_44f](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/8078f754-4f0a-4e1b-95c4-2dfffc6d978a)  
*Edit sky130A.tech File to solve the above DRC error*
![d3_192_44g](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/edd245f1-dcfb-426e-b957-76704779314b)
![d3_192_44h](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/76ed4276-527d-42f4-a055-24265e8660fa)  
**FOLLOW BELOW STEPS**  
*Step 1: Save your work.  Make sure to save your current design.**  
*Step 2: Load the Sky130 Tech File.  In Magic's terminal window, type the following command:tech load sky130A.tech ; A warning message might appear. Click "Yes" to proceed with loading the technology file.*  
*Step 3: Run Design Rule Check (DRC).  After loading the tech file, type the following command in the terminal: drc check*
This command will initiate a DRC check on your design using the loaded Sky130 technology rules.

![d3_192_44i](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/cbdf57f7-e707-4f3a-aab7-4b23a54d9443)  

*Similarly various DRC errors can be checked & by modifing the sky130A.tech it will be resolved*

**Screenshot of the Lectuer videos inline with above topic**
![d3_192_58](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5e1ca9bf-21c2-400d-892e-6d021c75a85e)  
![d3_192_62](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3ff19090-dc03-4d97-9fd4-b962fd6f8f1d)  
![d3_192_61](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/2ac49b01-cb02-4c0d-aaba-23b4d0694e14)  
![d3_192_59](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c6c963aa-17e1-484e-bf8c-60ef5998735a)  
![d3_192_55](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/00b693bd-2f67-4823-88e7-38559d6ae710)  
![d3_192_54](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/84892bcf-b2c9-48cd-95d2-592325426152)  
![d3_192_53](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a34dbebb-458c-47cf-b67e-68da4769245a)  
![d3_192_50](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/da9e05c6-35cb-43a6-a669-aa8f8ad21956)  
![d3_192_63](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/ab846a66-067d-46c9-a2bb-1b9386544c31)  

  
<a id="D4"></a>
## Topic 4 Pre-layout timing analysis and importance of good clock tree  
 **Pre-layout Timing Analysis and Importance of a Good Clock Tree in
OpenLANE**

This focuses on analyzing timing before the actual layout is created and
emphasizes the importance of a well-designed clock tree for optimal
performance.

1.  **Timing modelling using delay tables:**

-   These tables define the delays experienced by signals based on
    factors like net length, fanout (number of connected gates), and
    cell type.

-   OpenLANE likely uses pre-characterized delay tables from the
    foundry\'s Process Design Kit (PDK).

2.  **Convert grid info to track info:** (Assuming Magic layout tool is
    used)

-   Magic uses a grid system for layout design.

-   This step translates the grid information from Magic into routing
    track information for OpenLANE\'s understanding.

-   Tracks define the actual routing paths available for signals in the
    final chip layout.

3.  **Convert magic layout to std cell LEF:**

-   Magic layout files describe the physical design of the circuit.

-   LEF (Layout Exchange Format) is an industry-standard file format for
    representing standard cell information.

-   This step converts the Magic layout of custom cells into a standard
    cell LEF that OpenLANE can understand and integrate into the design.

4.  **Timing libraries (libs) and steps to include new cell in
    synthesis:**

-   Timing libraries contain information about the timing
    characteristics of standard cells in the design.

-   To include a new custom cell, you\'ll likely need to:

-   Create a Liberty (.lib) file characterizing the cell\'s timing
    behavior.

-   Update OpenLANE\'s configuration to include the new cell LEF and
    Liberty files.

-   Re-run synthesis to ensure the new cell is included in the design.

5.  **Configure synthesis settings to fix slack and include vsdinv:**

-   Slack refers to the difference between the available time for a
    signal to reach its destination and the actual time it takes.
    Negative slack indicates a timing violation.

-   Synthesis settings in OpenLANE can be adjusted to influence cell
    selection and placement, potentially improving slack.

**Importance of a Good Clock Tree:**

-   The clock tree distributes the clock signal to all parts of the
    design with minimal skew (delay variation).

-   A well-designed clock tree ensures that all flip-flops (registers)
    receive the clock signal at nearly the same time, avoiding timing
    violations and enabling reliable operation.  

**To view the routing track details, use this command as mentioned in image:**
![D4_0b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/eeaf7516-b49f-41e5-a215-fb180c149eae)
![D4_0a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/0b1c0b59-b580-4eaa-bf42-3ed9bc9e2e28)

**View after the command "grid 0.46um 0.34um 0.23um 0.17um"**
![D4_0d](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/997fa9dc-4671-4e22-8849-32066fde485c)  
*Chip I/O port positioned at track junction.*  

![D4_2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/b16b23cc-a5ad-4737-8cdc-4eff2dacef6c)  
![D4_2B](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/65de5684-1a7a-4600-ab8c-068110a678ba)  
![D4_3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/83a43d31-3568-456f-beb2-3e7a04a3a3cd)  

**convert magic layout to std cell LEF**

![D4_3a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/85fda6a6-7af9-42d0-b33c-fe9f8ae6d77c)  
*Defining Port*  
![D4_3_0](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3071bce2-3d0a-472a-bc54-e7bfd8ed6c17) 
![D4_3b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c91e9edd-71f3-4295-940f-50a42f21b12a)   
![D4_3b_0](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/039da565-101e-4474-9414-e5395f14f982)  
![D4_3b_1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/35170fc8-3cde-4dae-bc8d-2706f76119c4)  
![D4_3b_2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/244ab4d5-b41f-4f30-a030-b711b9bb6dc0)  
**Copy New created new .lef inside the picorv32a/src**
![D4_14a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/af114fb6-b280-4ed0-9c14-1f6f442de88e)  
![D4_14b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a4994335-6785-4f3a-8a13-30aaaee62cfd)  

*Modify config.tcl*
![D4_18](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/fe6b7d6e-4378-44dd-b597-e5b402945407)  
![D4_18a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/25629b4c-38ce-40e8-b14b-654cfd639e18)  
![D4_18b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/2c7896a5-15a5-495b-a97c-c8d2c76364da)

*OPENLANE: prep -design and run synthesis*
![D4_19a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d040a0cf-a3d3-4237-af1b-a4bd3a7d43e6)  
![D4_19b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/bb77c34a-e516-4f2c-adfc-749940898d50)
![D4_19c](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c4d6bc48-7b12-49e5-9724-01ace3ff3657)  

* Rerun synthesis after changing : SYNTH_STRATEGY , SYNTH_SIZING*  
![D4_19d](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/58c9dbd6-8670-4f71-b3ee-5e53576d45b8)
![D4_19e](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c1b590f7-a6d8-4c19-981d-94f9f0335250)  

*Run floorplan and Placment after adding sky130_vsdinv*  
![D4_48e](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/fba42481-05b4-4400-b708-e15355846911)  
![D4_48d](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/71c00a5d-7691-4bf6-af06-dc2b65609d74)  
![D4_48c](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/683a622f-43ae-4d3f-b236-2895770fbbd8)  
![D4_48b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/405d22fb-8ac8-4a06-a723-8423e9dec84b)  

*Inside the picorv32a Design you can observe sky130_vsdinv* 

![D4_48a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/eb1576b4-466c-4694-804d-4e90940e45b3)  
![D4_48a_0](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/52ca15d3-b1d4-4eef-ba03-c204a36ff699)  

*Configure OpenSTA after Synthesis : Create pre_sta.conf and my_base.sdc file as shown below & run command : sta pre_sta.conf in Openlane*  
![D4_72_3](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9a86ff8b-4c60-47dc-b90a-0cc0b3661b56)  
![D4_72_2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a9c07e71-5721-4224-ab60-4355d8c086cf)  
![D4_72_0](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5e6393e3-e5d1-461c-9c95-c4963e121796)
![D4_72_1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/bb2a396c-e026-4959-a519-d417b14d63da)
![D4_72_1a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d6812b6c-ab4a-4799-a332-fefc5eaae187)
![D4_72_1b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a34d19f3-4824-47c3-b1a9-3d7969ad3bf8)  

*Fix the Timing issue and overwrite the Verilog file using the command: write_verilog*

![D4_84a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d8c17da2-9513-4342-b672-4b1856a069d6)
![D4_84b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/225b3cb5-0958-4e2e-b0c2-42cb0cbd7261)
![D4_84c](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e475ffad-cc17-404b-8608-3cb19665dfa1)




**Understanding Delay Tables in VLSI**

**1. The Buffer Challenge:**

-   We use buffers to maintain signal integrity (strength) in a chip.

-   However, buffer sizing is crucial:

    -   All buffers in a level should be the same size (for
        consistency).  

        ![D4_28](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d336c545-b9a0-44e1-a8df-36d627eb503a)  

    -   But, individual delays need to vary depending on the load they
        drive (more load needs a stronger, potentially slower, buffer).  


**2. Enter the Delay Table:**

-   VLSI engineers created delay tables to address this challenge.

-   These tables act as timing models, pre-built and readily available
    online (often through e-foundries or platforms like Github).

**3. The Delay Table Structure:**

-   Imagine a 2D array, like a spreadsheet, with two main axes:  

![D4_33](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/58be8820-0c3c-42ef-b47b-f94502e88861)  

    -   Input Slew: This represents the incoming signal strength.

    -   Load Capacitance: This defines the amount of \"burden\"
        (connected gates) the buffer needs to drive.

**4. Finding the Right Delay:**

-   When designing your circuit, you know the input slew and load for a
    specific buffer.

-   You use the delay table to find the corresponding delay value for
    that combination.

**5. Interpolation for Missing Data:**

-   Sometimes, the exact input slew and load combination might not be
    present in the table.

-   The algorithm behind the delay table uses a technique called
    extrapolation.

-   It finds the closest data points and calculates the delay value
    based on those points.

**Benefit:**

By using delay tables, you can perform faster and more accurate timing
analysis during your VLSI design process.


#### Setup Timing Analysis: Ideal vs. Real Clocks

**What is Setup Timing Analysis?**

-   It checks if a signal arrives at a flip-flop (register) in time for
    it to be captured correctly.

-   Crucial for ensuring reliable chip operation.

**Ideal Clocks:**

-   **Perfect world:** Clocks arrive instantly and consistently at all
    flip-flops.

-   **Setup Time (Hold Time):** Minimum time a data signal needs to
    be **stable** (hold) **before** (setup) the clock edge for capture.

-   **Learning:** Ideal clocks simplify analysis, focusing on setup and
    hold times from data path delays.

**Real Clocks:**

-   **Reality check:** Clock signals experience delays due to routing
    and clock tree imperfections.

-   **Clock Skew:** Variation in arrival time of the clock signal across
    different parts of the chip.

-   **Learning:** Need to consider clock skew when analyzing setup time.
    Worst-case scenario: data arrives late at the slowest flip-flop due
    to combined data path delay and clock skew.

**Key Takeaway:**

-   Ideal clocks are a good starting point for understanding setup
    timing basics.

-   Real clocks require factoring in clock skew for a more accurate
    analysis in practical designs.

*Snapshot of the concepts from videos*  
![D4_60](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/6e512a94-e843-4d7d-aebb-56f0982207e0) 
![D4_61](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/f1bad60a-fcc8-42af-8a5e-f0a0fec54320) 
![D4_62](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e4971c57-48a8-47a3-b309-8284d5af206d)  
![D4_64](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3ea012c3-c3b6-42d4-bad1-1c4643a4071d)  
![D4_66](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/6f39816f-02c1-487b-aee9-bfe2a7bfbdee) 
![D4_68](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/133ddc58-3223-4d06-be97-9504ee038d15)  
![D4_100_1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/7fb5e45a-767b-4083-978b-605aab1a0ca0)  
![D4_100_2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/0ca0e21d-865f-473a-837d-ccff21683e32)  
![D4_100_7](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/db8f4cf1-e495-455d-ad42-4b2128f80892)  
![D4_100_10](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/e16ba784-b44d-40f8-9865-c5c1c8c6d552)  
![D4_100_11](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/57b5fc9e-ea6d-450f-ba66-b385ef8ccbbe)  
![D4_100_12](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a4d5c91f-c6e4-46f9-9448-e51e254c2af4)  
![D4_100_13](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/f3ba15f6-f248-4751-a6ca-424104583725)  
![D4_100_13a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/6d1e2df1-14a1-4d6d-82e2-5899744014df)  
![D4_100_14](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d78ccf53-3a1c-44fd-8caa-c9504b264b5f)  
![D4_100_14a](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a2176a6e-b25c-44d3-81d3-0de86dc6852e)  
![D4_100_15b](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a0faae36-7718-44a4-bc52-e484b4453dc6)  
![D4_100_15e](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5007b8ea-9ac8-4f47-bfee-26f080b2b597)  
![D4_100_17](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/c730818e-5424-4a33-8417-2dba0653020d)  
![D4_100_25](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/8bca7059-b932-4253-b0ef-7c9cb332aee8)  
![D4_100_26](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4edd683b-1a72-4d52-9fa8-ce3de885697d)  
![D4_100_27](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/57c19ddd-a8b7-445b-b160-c19d1f4fb224)  
![D4_100_34](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9548bec7-4641-4eb8-a570-4c50746cd15c)  


<a id="D5"></a>  
## Topic 5 Final steps for RTL2GDS using tritonRoute and openSTA  
**1. Routing and Design Rule Check (DRC)**

-   **What is Routing?**

    -   The process of connecting components (gates) in a design using
        metal wires.

    -   Think of it like creating a network of roads on a map to connect
        different cities.

-   **What is DRC?**

    -   A set of electrical and physical rules that ensure the
        manufacturability of a design.

    -   DRC checks for things like minimum wire width, spacing between
        wires, and proper connections.

    -   Imagine checking the road network for things like lane width,
        safety clearances, and proper intersections.

    -   

-   **Example:**

    -   You want to connect two logic gates (cities) with a wire (road).

    -   Routing would determine the path of the wire.

    -   DRC would ensure the wire width is thick enough to carry current
        (lane width) and there\'s enough space between it and other
        wires for reliable operation (safety clearance).

**2. Power Distribution Network (PDN) and Routing**

-   **What is PDN?**

    -   A network of wires that delivers power (electricity) to all
        parts of the design efficiently.

    -   Think of it like the power grid that supplies electricity to
        homes and businesses.

    -   

-   **Relationship with Routing:**

    -   Regular routing shares space with PDN routing.

    -   PDN routing needs careful planning to ensure stable voltage
        delivery.

    -   It\'s like having dedicated power lines alongside regular roads
        to avoid overloading the system.

    -   

-   **Example:**

    -   Your design needs stable power for all gates (cities) to
        function properly.

    -   PDN routing creates dedicated \"power lines\" to deliver this
        power efficiently.

    -   Regular routing for signal connections happens alongside these
        power lines, but with proper spacing to avoid interference.

**3. TritonRoute Features for RTL2GDS using TritonRoute and OpenSTA**

GDS (GDSII stream - a file format for chip layout), OpenSTA (a static
timing analysis tool), and TritonRoute (a detailed routing tool).

-   **TritonRoute for Detailed Routing:**

    -   Takes a netlist (connectivity information) and constraints from
        OpenSTA.

    -   Generates detailed routing patterns between components based on
        those constraints.

    -   Imagine using specialized software to design the actual road
        network layout based on city locations and traffic flow
        analysis.

    -   

-   **OpenSTA for Timing Analysis:**

    -   Analyzes the timing characteristics of the design.

    -   Provides constraints for routing to ensure signals arrive at
        their destinations within the required time.

    -   Think of it as a traffic flow analysis tool that helps determine
        optimal road layouts to avoid congestion.

    -   

-   **Example:**

    -   You have an RTL design (city map) and need to create the
        physical layout (road network) in GDS format.

    -   OpenSTA analyzes the timing requirements for signals (traffic
        flow).

    -   TritonRoute uses this information and the netlist to create
        detailed routing patterns (actual road layout) that meet the
        timing constraints.

Overall, these concepts work together to ensure a manufactural and
functionally correct chip design.  

**Screenshot from the video session of the topic**

![D5_1](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/fdd8f8a6-31c5-4706-a013-1968e775965d)  
![D5_2](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/5531eebf-527b-4a22-a53f-1bb83a2efafe)
![D5_6](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/194e6c43-e3b0-4b3c-a89b-054507c716ac)  
![D5_10](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/1dbe07db-df74-4027-b480-c34c5b9e9321)  
![D5_14](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/fb1f38b3-19d4-4ff5-836f-ae133be3ed79)  
![D5_15](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/863c3913-929e-45bb-8616-42085e96b388)  

![D5_22](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/3f142265-3fb8-4370-86f4-a254e2930e69)  
![D5_27](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/9e553848-820e-4990-9334-6047de571921)
![D5_30](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/08793f15-c98e-4396-bdc2-8bc2996544f6)
![D5_31](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/a01a04a4-40e8-43b5-a39d-737bba8cb29e)
![D5_37](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/440e0835-d136-4d8e-be14-a94ac739febf)

![D5_41](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/4e9995e7-99c5-4e73-bdaa-df8bcd8d9732)
![D5_44](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/14a2613b-2d78-4756-9308-4798b09259d6)
![D5_49](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/0e1307b1-bc52-4a4c-a73f-ebe61e3c2169)

![D5_51](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/2b042fdf-e66c-488c-ae78-7c680a2b5710)
![D5_52](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/d0eb280f-07a1-4cc2-9a20-b7b8ca6bbbfe)

![D5_55](https://github.com/ursbestfriend/NASSCOM-VSD-SoC-Design/assets/125972379/71fa9544-eae5-4792-99ec-eecbe1776b15)

