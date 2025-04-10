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
    
Instruction 1   : addi sp, sp, -16  
   
    ![Screenshot 2025-04-05 223656](https://github.com/user-attachments/assets/0c616b86-321d-4371-8e91-548862ef65ab)
    
Instruction 2     :	sd	ra,8(sp) 
    ![image](https://github.com/user-attachments/assets/f0c8655d-6b22-4c9c-8e43-8dad8aba79aa)
	
Instruction 3	    : li	a2,15 
	![Screenshot 2025-04-05 224520](https://github.com/user-attachments/assets/5f155c5b-1e4f-4beb-b00f-220a7dbc97f0)

Instruction 4	    : lui	a0,0x21 
	![Screenshot 2025-04-05 224539](https://github.com/user-attachments/assets/7c23bf27-6295-4453-abb0-4137ec475ae1)

Instruction 5	    : ld	ra,8(sp) 
	![Screenshot 2025-04-05 224554](https://github.com/user-attachments/assets/e3addf08-eb07-4d1a-b3a9-f3c45fad6479)
		
Instruction 6	    : mv	a1,a0 
	![Screenshot 2025-04-05 224608](https://github.com/user-attachments/assets/2444f236-74c0-4034-8712-f41a6558c5c1)

Instruction 7	    : j 12df8 
	![Screenshot 2025-04-05 224622](https://github.com/user-attachments/assets/33b64723-0f7c-4e1a-834e-c4ace4a4ee95)

Instruction 8	    : lw  a5,80(s0) 
	![Screenshot 2025-04-05 224635](https://github.com/user-attachments/assets/3186ccf1-3bdc-43a5-a2f7-e78e7ab1874f)

Instruction 9	    : lh a3,16(a4) 
	![Screenshot 2025-04-05 224650](https://github.com/user-attachments/assets/1a05da89-1384-4a8d-8c02-ff975a0360f8)

Instruction 10	  : slli a5,a3,0x30 
	![Screenshot 2025-04-05 224704](https://github.com/user-attachments/assets/87c951cb-16f1-4c51-bae8-289cf662c51f)

Instruction 11	  : srli  a5,a5,0x30
	![Screenshot 2025-04-05 224720](https://github.com/user-attachments/assets/92d4f6a5-a3f8-4e47-a4c8-378c706c773f)

Instruction 12	  : and  a3,a2,a3 
	![Screenshot 2025-04-05 224734](https://github.com/user-attachments/assets/d2244559-13ae-434d-900c-efa378cd6f7c)

Instruction 13	  : sw  a5,-28(s0) 
	![Screenshot 2025-04-05 224747](https://github.com/user-attachments/assets/75284f02-1cac-4923-b5ff-6874ecaf5a40)

Instruction 14	  : addiw a5,a5,1 
	![Screenshot 2025-04-05 224800](https://github.com/user-attachments/assets/6b4d0df5-852c-49cb-b578-396340189094)

Instruction 15	  : addw  a5,a4,a5

   ![Screenshot 2025-04-05 224809](https://github.com/user-attachments/assets/4f5ef5b8-9ecd-433b-8da8-850f0d155899)


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
 

    Assembly Code : 

    
	Instruction 1 : add r6,r1,r2.(i1)  ---> 1+2 =3 : HEX 02208300

    ![Screenshot 2025-04-10 112045](https://github.com/user-attachments/assets/5c18e33f-29d7-4d92-9aa9-73dec25ff6f3)

	Instruction 2:  sub r7,r1,r2.(i2)  : HEX 02209380
 ![image](https://github.com/user-attachments/assets/85a67340-1745-418c-b85e-8a810486e316)

	Instruction 3:  and r8,r1,r3.(i3) : HEX 0230a400
 ![image](https://github.com/user-attachments/assets/e6641b77-8a86-4f1d-a63f-bdf97a7c3a26)

	Instruction 4:  or r9,r2,r5.(i4) : HEX 02513480
 ![image](https://github.com/user-attachments/assets/b12cdcc2-11f1-4060-bd27-9a4356666610)

	Instruction 5:  xor r10,r1,r4.(i5) : HEX 0240c500
 ![image](https://github.com/user-attachments/assets/5c80275e-7472-4d9b-aa82-49d24ab25006)

	Instruction 6:  slt r11,r2,r4.(i6) : HEX 02415580
 ![image](https://github.com/user-attachments/assets/b937067f-f18f-4039-ac28-206d00ffb048)

	Instruction 7:  addi r12,r4,5.(i7) : HEX 00520600
 ![image](https://github.com/user-attachments/assets/17caa61f-0a35-4364-934e-c1e285ed2473)

	Instruction 8:  sw r3,r1,2.(i8)  : HEX 00209181
 ![image](https://github.com/user-attachments/assets/a8e96a85-6031-4de4-b835-175d487d816b)

	Instruction 9:  lw r13,r1,2.(i9)  : HEX 00208681
 ![image](https://github.com/user-attachments/assets/6312726c-8e3e-4de7-a2f6-3888f1f96439)

	Instruction 10:  beq r0,r0,15.(i10)  : HEX 00f00002
 ![image](https://github.com/user-attachments/assets/5b235e79-e4c6-4464-b199-ead5fc46a79f)

	Instruction 11:  add r14,r2,r2.(i11)  : HEX 00210700
 ![image](https://github.com/user-attachments/assets/9d99dd25-7784-4e0f-b042-4b0042068bba)

