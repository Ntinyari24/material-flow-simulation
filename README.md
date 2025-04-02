# Particle Size Distribution and Crusher Simulation

## Overview
This program simulates a **crusher process** by taking an initial **Particle Size Distribution (PSD)** and applying a crushing operation based on user-defined crusher settings. It calculates and displays the **final PSD** and the **overall reduction ratio** after crushing.

## Features
- Accepts user input for **feed rate** and **crusher size range**.
- Uses **randomized calculations** to simulate crushing.
- Displays the **initial and final Particle Size Distribution (PSD)**.
- Computes and prints the **overall reduction ratio**.

## How It Works
1. The program initializes a sample **PSD** with predefined sizes and percentages.
2. The user provides:
   - **Feed rate** (ton/hour or kg/s).
   - **Minimum and maximum crusher size** (in mm).
3. The program randomly adjusts the particle sizes within the crusher range.
4. The final **PSD** and **reduction ratio** are calculated and displayed.

## Requirements
- C++ compiler (e.g., GCC, Clang, MSVC)
- Standard C++ libraries (no external dependencies)

## Compilation & Execution
### Compile the program:
```sh
 g++ crusher_simulation.cpp -o crusher_simulation
```

### Run the executable:
```sh
 ./crusher_simulation
```

## Example Input & Output
### User Input:
```
Enter the feed rate (ton/hour or kg/s): 100
Enter the minimum crusher size (mm): 0.5
Enter the maximum crusher size (mm): 2.0
```

### Example Output:
```
Particle Size Distribution (PSD):
Size: 1.32 mm - Percentage: 30%
Size: 0.98 mm - Percentage: 30%
Size: 1.75 mm - Percentage: 30%

Overall Reduction Ratio: 1.24
```

## Possible Improvements
- Allow users to enter custom **PSD values**.
- Implement **graphical representation** of size distribution.
- Improve accuracy by applying **real-world crushing models**.

## Author
- **Keren**

## License
This project is **open-source** and can be used for educational or research purposes.

