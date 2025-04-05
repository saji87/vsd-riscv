# RISC V Internship 

  ## TASK 1 
    1. Create a GitHub repository named "vsd-riscv" 
    2. Watch the video for to understand the program flow 
    3. Install the RISC-V toolchain using the VDI link mentioned in the attached PDF  
    4. Refer to this C based lab video and RISC-V based lab video and perform the same steps on your machine 
    5. Capture lab snapshots (with the current date/time visible), and upload them to your GitHub repository along with brief details. 

  ## TASK 2 
    1. Fill up the form - https://forms.gle/wyXTTNccQanhPuBa8  
    2. Review the provided SPIKE Simulation video: Video Link 
    3. Run the simulation and observe the performance under the -O1 and -Ofast compiler optimization flags. 
    4. Write a simple C program (any basic application). 
    5. Compile the C program using RISC-V GCC/SPIKE with the above optimization options. 
    6. Generate and collect the RISC-V object dump for both -O1 and -Ofast. 
    7. Upload snapshots of the following to your GitHub repository: 
        a. The compiled C code. 
        b. The RISC-V object dump for each optimization level (-O1 and -Ofast). 

![1](https://github.com/user-attachments/assets/7fb467d8-8ba4-4c11-add4-a25e1f8b2b99)

**Normal O1 Compilation**

![2](https://github.com/user-attachments/assets/1b3511e4-5e8f-4479-9fbd-e6ec9d069236)
![3](https://github.com/user-attachments/assets/00fab5d7-a080-43b4-8d58-0f25d0fbb328)

**OFast Compilation**


![5](https://github.com/user-attachments/assets/47cecfc8-0e38-4bfd-9a87-855597261789)
![5_calc](https://github.com/user-attachments/assets/b27aa13d-c6ec-4c68-8b5b-b68c09dd92b6)

  ## TASK 3  
    1. Review the RISC-V software documentation (link) to understand the R, I, S, B, U, and J instruction types. 
    2. Check out this sample GitHub repository for a visual guide on decoding RISC-V instructions: Sample Repo. 
    3. From the riscv-objdump of your application code, identify 15 unique RISC-V instructions. 
    4. For those 15 instructions, determine the exact 32-bit instruction code in their respective instruction type formats. 
    5. Upload the 32-bit instruction patterns to your GitHub repository. 

 ## Task 4: Functional Simulation of RISC-V Core 

    Objective: Perform a functional simulation of the given RISC-V Core Verilog netlist and testbench. 
    Steps: 
      1. Download Files: 
        Get the Verilog netlist from RISC-V Core Verilog Netlist. 
        Get the testbench from Testbench for RISC-V Core. 
      2. Set Up Simulation Environment: 
        Ensure you have a suitable simulation tool (e.g., iverilog, gtkwave). 
        Load the Verilog netlist and testbench into the simulator. 
      3. Run Functional Simulation: 
        Simulate the design using the testbench.
        Check the functional correctness of the core by observing the output signals.
      4. Capture Waveforms:
        Generate and save waveform snapshots for the executed commands during the simulation.
      5. Upload Results to GitHub:
        Update your GitHub repository.
        Upload the waveform snapshots and simulation results to your GitHub.
        Include a brief description of your work in the repository.
    Reference Resources:
      Official GitHub repository: RISC-V Core GitHub Repo.
      Use the reference document for additional guidance.
