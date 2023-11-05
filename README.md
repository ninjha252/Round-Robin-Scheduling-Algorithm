# Round-Robin-Scheduling-Algorithm


# Round Robin Scheduling Project

This repository is dedicated to a project that simulates the Round Robin (RR) scheduling algorithm. The Round Robin scheduling algorithm is a pre-emptive CPU scheduling method that is widely used in time-sharing systems. It handles all processes without priority, ensuring a high degree of responsiveness for all tasks.

## Project Description

Round Robin scheduling assigns a fixed time unit, termed a quantum, to each process in the process queue. The CPU services the processes in the order of their arrival, for a period not exceeding the predefined quantum. If a process's execution is not completed within the quantum, it is placed back in the queue, and CPU control is transferred to the next process.

This project provides an implementation of this scheduling algorithm in C++. It includes calculating waiting times and turnaround times for each process to analyze the efficiency of the scheduling strategy.

## Features

- Implementation of the Round Robin scheduling algorithm in C++.
- Simulation of process scheduling with variable arrival times and burst times.
- Calculation of waiting times and turnaround times for processes.

## How to Use

To simulate the Round Robin scheduling:

1. Clone the repository to your local machine.
2. Navigate to the cloned directory.
3. Compile the C++ code with a command like `g++ -o round_robin round_robin.cpp` (assuming your C++ file is named `round_robin.cpp`).
4. Run the executable with `./round_robin`.

## Contributing

Interested in contributing? Great! Here's how you can:

1. Fork the repository on GitHub.
2. Clone your fork to your local machine.
3. Make your changes and test them.
4. Push the changes to your fork.
5. Submit a pull request with a comprehensive description of changes.

## Contents of the Repository

- `README.md` - This README file.
- `index.html` - The main HTML file for the GitHub Pages website.
- `about.html` - HTML file containing detailed information about the Round Robin scheduling algorithm and the project code.
- `style.css` - The stylesheet for the website.
- `script.js` - Any JavaScript associated with the website.
- `round_robin.cpp` - The C++ source code for the Round Robin simulation.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- This project is created for educational purposes.
- Thanks to all contributors who have helped to improve the code and documentation.

We hope this project aids in understanding the inner workings and efficiency of the Round Robin scheduling algorithm.
