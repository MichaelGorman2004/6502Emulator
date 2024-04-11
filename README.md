# Author: Michael Gorman

# 6502 Microprocessor Emulator in Python

This project is a Python-based emulator for the 6502 microprocessor, a popular 8-bit processor used in many vintage computers and gaming consoles. The emulator accurately replicates the behavior and instruction set of the original 6502 hardware, providing a platform for running and testing 6502 assembly language programs.

## Features

- Accurate emulation of the 6502 microprocessor
- Support for the complete 6502 instruction set
- Customizable memory configuration
- Debugging features, including breakpoints, step-by-step execution, and register inspection
- Integration with a command-line interface and a web-based frontend
- Comprehensive test suite to ensure emulation accuracy
- Cross-platform compatibility

## Getting Started

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/Python-6502-Emulator.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

### Usage

1. Navigate to the project directory:
   ```
   cd 6502-emulator
   ```

2. Run the emulator with a 6502 assembly language program:
   ```
   python emulator.py program.asm
   ```

   Replace `program.asm` with the path to your 6502 assembly language file.

3. Interact with the emulator using the command-line interface or the web-based frontend.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [6502.org](http://6502.org/) - Valuable resource for 6502 documentation and tutorials
- [py65](https://github.com/mnaberez/py65) - Python-based 6502 emulator that served as inspiration for this project
