---
title: Projects
layout: template
filename: projects
--- 

# Portfolio Projects are ordered by date.

## Project 1: Deep Learning Overview Report
- Coursework for the 3rd Year Deep Learning module at Imperial College London in the Electrical and Electronic Engineering Department
- Study into the fundamental topics of Deep Learning, including:
    - Network Training
    - Convolutional Neural Networks (CNN's)
    - Recurrent Nerual Networks (RNN's)
    - Autoencoders
    - Variational Autoencoders (VAE's)
    - Generative Adverserial Networks (GAN's)
    - Reinforcement Learning (RL)
- Experiments conducted using Google Colab and Keras API
- [Deep Learning Overview Report](https://github.com/horsada/Horsada_Portfolio/blob/main/Summer%20Design%20Project%20-%20Group%2020%20-%20WAP.pdf)

## Project 2: Signal Processing Overview Report
- Coursework for the 3rd Year Advanced Signal Processing module at Imperial College London in the Electrical and Electronic Engineering Department
- Study into the fundamental topics of Signal Processing, including:
    - Random Variables
    - Linear Stochastic Models
    - Estimation Theory
    - Least Squares Method
    - Adaptive Estimation and Adaptive Filters
- Experiments conducted in MATLAB
- [Signal Processing Report](https://github.com/horsada/Horsada_Portfolio/blob/main/Summer%20Design%20Project%20-%20Group%2020%20-%20WAP.pdf)

## Project 3: [Query Processing](https://github.com/horsada/QueryProcessing)
- Implementation of a three-way join in the context of relational querying
- One of the joins was implemented using a hash-join, while the other was implemented with a sort-merge join
- The query can be defined in SQL as:
    - select sum(large1.c * large2.c * small.c) from large1, large2, large3 where large1.a = large2.a and large2.a
    = small.a and x * large1.b + y * large2.b + z * small.b > threshold;
- Implemented using C++ 20 and Ubuntu 20.04 OS


## Project 4: [Semi-Autonomous Rover](https://github.com/horsada/WAP_Rover)
- Year 2 Summer Design Project.
- Team of 6, each with their own subsystem.
- I worked on the Vision component, which can be found in the Vision folder
- Implemented on an FPGA and D8M Terasic Camera, using Quartus and Eclipse
- [Year 2 Summer Design Project Report](https://github.com/horsada/Horsada_Portfolio/blob/main/Summer%20Design%20Project%20-%20Group%2020%20-%20WAP.pdf)

![Rover_3D_Model](/Rover_3D_Model.JPG) ![Coloured_Ping_Pong_Balls](/coloured_ping_pong_balls.JPG)

## Project 5: [C -> MIPS assembly Compiler](https://github.com/horsada/Morningism)
- Implemented using Flex/Yacc for lexing and parsing, then traversing the AST is done using C++.
- Input = C-- file, Output = MIPS assembly.
- Note: This project does not have an official PDF report; the details can be found in the **readme.md** file.

## Project 6: [FPGA-based Ping Pong game](https://github.com/horsada/InfoProcessing2020)
- FPGA hardware and software programming done using Quartus Prime and Eclipse.
- Intel DE-10 Lite FPGA with accelerometer for interacting with the game.
- Use C for high level synthesis
- Game implemented in Python.
- AWS Server to communicate between 2 players.
- [FPGA-based Ping Pong game PDF Report link](https://github.com/horsada/Horsada_Portfolio/blob/main/IP_Project_Report.pdf)

![FPGA_DE10_LITE](/FPGA_board.JPG)

## Project 7: [MIPS CPU](https://github.com/horsada/MIPS_CPU)
- Implemented in SystemVerilog.
- Non-pipelined 3 cycle CPU based off the MIPS 1 ISA.
- Harvard-based architecture.
- [MIPS CPU Project Report PDF link](https://github.com/horsada/Horsada_Portfolio/blob/main/mips_data_sheet%20(2).pdf)

![MIPS_CPU_Structure](/MIPS_CPU_Structure.JPG)

## Project 8: [Circuit Simulator](https://github.com/horsada/Circuit_Simulator)
- Implemented in C++.
- Similar to LTSpice.
- Converts a netlist of passive components (resistors, capacitors and cnductors) and 
voltage and current sources into graphical representations of voltage/current of each
component over time. 
- Graphs are done using MATLAB.
- [Circuit Simulator Project Report PDF link.](https://github.com/horsada/Horsada_Portfolio/blob/main/ELEC40006.-.Final.Report%20(1).pdf)

![LTSPICE_Circuit_1](/Example_Circuit.JPG)   ![LTSPICE_graph_1](/Circuit_MATLAB_Graph.JPG)
