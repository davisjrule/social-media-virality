# Social Media Virality Simulation

## Project Overview
This project simulates the spread of content on a social media platform using a network-based model. It investigates how varying factors such as sharing probability, user online status, and content visibility duration influence the virality of posts. The simulation aims to provide insights into the dynamics of content spread and identify key factors that enhance or inhibit virality in digital social networks.

## Key Features
- **Model Initialization**: Set up a Watts-Strogatz small-world network to simulate a social media environment.
- **Dynamic Updates**: Simulate user interactions and content sharing with variable online statuses and sharing behaviors.
- **Parameter Sweeps**: Explore the effects of different sharing probabilities, user online probabilities, and content durations on virality.
- **Visualization**: Generate network graphs and heatmaps to visually represent how changes in parameters affect content virality.

## Libraries Used
- `NetworkX`: Used for creating and manipulating complex network structures.
- `Matplotlib`: Employed for generating plots and heatmaps to visualize the data.
- `NumPy`: Utilized for efficient numerical computations.

## Setup and Running the Simulation
To run this simulation, ensure you have Python installed along with the necessary libraries. You can install the required libraries using pip:

```bash
pip install networkx matplotlib numpy
```

To execute the simulation, open the file as a notebook in Google Colab and run the cells as is. 