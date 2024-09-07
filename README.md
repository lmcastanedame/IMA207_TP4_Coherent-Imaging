# Coherent Imaging Analysis (IMA207)

This project is part of the IMA207 course and focuses on the analysis and simulation of coherent imaging systems. The primary goal is to understand how coherent light behaves in different imaging scenarios, including propagation, interference, and diffraction, through computational simulations.

## Project Description

The project simulates various aspects of coherent imaging systems, including light propagation and image reconstruction. Coherent imaging, commonly used in fields such as microscopy and holography, relies on the interference patterns of coherent light. This project implements mathematical models to simulate these patterns and study their impact on image formation.

## Project Structure

The repository contains the following key files and directories:

- **main.py**: The main script where coherent imaging simulations are implemented.
- **imaging_systems/**: A directory containing simulation setups for different coherent imaging systems.
- **utils.py**: Utility functions for handling image processing and simulation tasks.
- **notebooks/**: Jupyter notebooks for testing and visualizing coherent imaging simulations.
- **requirements.txt**: A file listing all the dependencies needed to run the project.
- **README.md**: This file with detailed information about the project.

## How to Use

### Prerequisites

- Python 3.x
- Libraries: NumPy, SciPy, Matplotlib

Install the required libraries with:

```bash
pip install -r requirements.txt
```

### Running the Project

To simulate coherent imaging and view the results, follow these steps:

1. Prepare or select an imaging setup from the `imaging_systems/` directory.
2. Run the main simulation script:

    ```bash
    python main.py
    ```

3. The output will display visual results of the simulation, including light propagation patterns, interference, and diffraction effects.

### Key Steps in the Process

1. **Define Imaging System**: Specify the parameters of the coherent imaging system, such as light source, aperture, and object.
2. **Simulate Light Propagation**: Compute how light propagates through the system, taking into account diffraction and interference.
3. **Reconstruct Image**: Use the interference patterns to reconstruct the final image.
4. **Visualize Results**: Plot the simulation results to analyze coherent light behavior.

## Purpose

This project helps in understanding the fundamental principles of coherent imaging, which has applications in advanced optical systems such as holography and microscopy. By simulating these processes computationally, the project provides insights into how coherent light interacts with objects to form detailed images.

## Technologies

- **Language**: Python
- **Libraries**: NumPy, SciPy, Matplotlib
- **Tools**: Jupyter Notebooks for visualization and experimentation
