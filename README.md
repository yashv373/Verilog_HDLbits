# HDLBits Verilog Practice Repository

Welcome to my HDLBits Verilog practice repository! This repository is a collection of my solutions and documentation for the exercises on [HDLBits](https://hdlbits.01xz.net/), an excellent platform to learn and practice Verilog HDL. Here, I explore the concepts of digital design and hardware description language by solving problems one question at a time. 

## About HDLBits

[HDLBits](https://hdlbits.01xz.net/) is an interactive platform designed to help students and engineers practice and learn Verilog, a hardware description language used for designing digital systems such as FPGAs and ASICs. The platform offers a wide range of problems, from basic syntax and constructs to advanced digital design challenges.

Check out my HDLBits profile: [Yashvardhan Singh's HDLBits Profile](https://hdlbits.01xz.net/wiki/Special:VlgStats/17520D2AE8547C32)

## Repository Structure

This repository is organized question by question, with solutions, not in folders like the website though.
Will try my best to comment everything out to make it easy for anyone to understand the code!

```
HDLBits-Verilog-Practice/
|-- README.md            # This file
|-- Basics/              # Basic syntax and fundamental concepts
|-- Gates/               # Combinational logic and gates
|-- Adders/              # Adders and arithmetic circuits
|-- Multiplexers/        # Multiplexer-based designs
|-- Sequential/          # Sequential circuits (flip-flops, counters, etc.)
|-- FSM/                 # Finite state machines
|-- Advanced/            # Advanced digital design problems
|-- Testbenches/         # Testbenches for simulating and verifying solutions
```

Each folder contains:
- Verilog files (`.v`) for the solution.
- Comments and notes on the approach taken.
- A `README.md` in each subdirectory explaining the topic.

## Getting Started

1. **Clone this repository**:
   ```bash
   git clone https://github.com/<your-username>/HDLBits-Verilog-Practice.git
   ```

2. **Navigate through the folders** to explore solutions for each problem.

3. **Test the solutions** using a Verilog simulator such as ModelSim, Vivado, or Icarus Verilog. 
   - To run a simulation with Icarus Verilog, use:
     ```bash
     iverilog -o output_file testbench.v solution.v
     vvp output_file
     ```

4. **Understand the concepts** through the notes and comments provided in the code.

## Why This Repository Exists

I created this repository to:
- Track my progress as I practice and learn Verilog HDL.
- Share my solutions with others who may benefit from them.
- Document my thought process and learning journey.
- Receive feedback from the open-source community.

## Topics Covered

### Basics
Fundamentals of Verilog syntax, module definitions, and simple combinational logic circuits.

### Gates
Design and implementation of basic gates, such as AND, OR, XOR, and their combinations.

### Adders
Arithmetic circuits including half adders, full adders, and ripple-carry adders.

### Multiplexers
Design and use of multiplexers and demultiplexers in digital logic.

### Sequential
Sequential logic circuits, including flip-flops, latches, counters, and shift registers.

### FSM
Finite state machines for control logic, including Moore and Mealy state machines.

### Advanced
More complex digital design challenges, such as parameterized modules and custom designs.

### Testbenches
Testbench examples for simulating and verifying the correctness of the solutions.

## Contributions

Feel free to explore the repository and contribute! If you spot errors or have suggestions for improvement, open an issue or submit a pull request.

### How to Contribute
1. Fork the repository.
2. Create a new branch for your changes.
3. Make your edits and commit.
4. Push to your branch and create a pull request.

## Tools Used
- **Icarus Verilog**: A free Verilog simulator.
- **GTKWave**: A waveform viewer for analyzing simulation results.
- **HDLBits**: Problem-solving platform.

## Contact
For any queries or feedback, feel free to reach out:
- **Email**: yvs.373@gmail.com
- **HDLBits Profile**: [Yashvardhan Singh](https://hdlbits.01xz.net/wiki/Special:VlgStats/17520D2AE8547C32)

## Acknowledgments
- Special thanks to the creators of HDLBits for this incredible learning platform.
- The open-source community for guidance and inspiration.

## License
This repository is licensed under the [MIT License](LICENSE). Feel free to use, modify, and share the content as per the license terms.

---

Happy coding and learning Verilog!
