RISC V Internship 

  TASK 1 <br />
    1. Create a GitHub repository named "vsd-riscv" <br />
    2. Watch the video for to understand the program flow <br />
    3. Install the RISC-V toolchain using the VDI link mentioned in the attached PDF  <br />
    4. Refer to this C based lab video and RISC-V based lab video and perform the same steps on your machine <br />
    5. Capture lab snapshots (with the current date/time visible), and upload them to your GitHub repository along with brief details. <br />

  TASK 2 <br />
    1. Fill up the form - https://forms.gle/wyXTTNccQanhPuBa8 <br /> 
    2. Review the provided SPIKE Simulation video: Video Link <br />
    3. Run the simulation and observe the performance under the -O1 and -Ofast compiler optimization flags. <br />
    4. Write a simple C program (any basic application). <br />
    5. Compile the C program using RISC-V GCC/SPIKE with the above optimization options. <br />
    6. Generate and collect the RISC-V object dump for both -O1 and -Ofast. <br />
    7. Upload snapshots of the following to your GitHub repository: <br />
        a. The compiled C code. <br />
        b. The RISC-V object dump for each optimization level (-O1 and -Ofast). <br />

![1](https://github.com/user-attachments/assets/7fb467d8-8ba4-4c11-add4-a25e1f8b2b99)

**Normal O1 Compilation**

![2](https://github.com/user-attachments/assets/1b3511e4-5e8f-4479-9fbd-e6ec9d069236)
![3](https://github.com/user-attachments/assets/00fab5d7-a080-43b4-8d58-0f25d0fbb328)

**OFast Compilation**


![5](https://github.com/user-attachments/assets/47cecfc8-0e38-4bfd-9a87-855597261789)
![5_calc](https://github.com/user-attachments/assets/b27aa13d-c6ec-4c68-8b5b-b68c09dd92b6)

  TASK 3  <br />
    1. Review the RISC-V software documentation (link) to understand the R, I, S, B, U, and J instruction types. <br />
    2. Check out this sample GitHub repository for a visual guide on decoding RISC-V instructions: Sample Repo. <br />
    3. From the riscv-objdump of your application code, identify 15 unique RISC-V instructions. <br />
    4. For those 15 instructions, determine the exact 32-bit instruction code in their respective instruction type formats. <br />
    5. Upload the 32-bit instruction patterns to your GitHub repository. <br />
