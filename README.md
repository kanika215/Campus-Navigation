# Campus Navigation Bot (10×10 Grid)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![License](https://img.shields.io/badge/License-MIT-green)

A **Jupyter Notebook project** that helps users navigate a simplified campus using a **10×10 grid** and **reinforcement learning** algorithms such as **Q-Learning**, **SARSA**, and **Monte Carlo Control**. This bot determines the **shortest and optimal paths** between grid locations.

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Results & Visualization](#results--visualization)  
7. [Future Improvements](#future-improvements)  
8. [License](#license)  

---

## Project Overview
The **Campus Navigation Bot** operates on a **10×10 grid environment** representing a simplified campus map.  
It uses **reinforcement learning techniques** to learn the most efficient path between a **START** and **GOAL** position.

### Key Points
- Supports multiple algorithms: **Q-Learning**, **SARSA**, and **Monte Carlo Control**.  
- Visualizes the **grid**, **path**, and **value distribution** using **matplotlib** and **seaborn**.  
- Computes **total cost**, **number of steps**, and **optimal path**.

---

## Features
- Interactive **Jupyter Notebook** with clean modular code.  
- Automatic calculation of **optimal path** in the 10×10 map.  
- Visual outputs:
  - Navigation path visualization using arrows or color grid
  - State-value heatmaps
  - Comparison graphs for steps and cost

---

## Technologies Used
- **Python 3.x**
- **Jupyter Notebook**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Campus-Navigation-Bot.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Campus-Navigation-Bot
   ```

3. Install dependencies:
   ```bash
   pip install numpy matplotlib seaborn
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Usage
- Open **Campus Navigation Bot.ipynb** in Jupyter Notebook.
- Run cells sequentially to train navigation algorithms.
- Modify `START` and `GOAL` coordinates to navigate between different grid points.
- Visualizations will generate automatically for each algorithm.

---

## Results & Visualization
- Optimal path visualization using movement arrows.
- Heatmaps of learned state values for:
  - **Q-Learning**
  - **SARSA**
  - **Monte Carlo Control**
- Side-by-side comparison of **cost** and **steps**.

---

## Example Screenshots
(Add actual images after generating results.)

```
images/path_visualization.png
images/value_heatmap.png
```

---

## Future Improvements
- GUI interface for interactive navigation.
- Real campus map instead of grid model.
- Multi-agent navigation.
- Integration of advanced RL (DQN, Actor-Critic, PPO, etc.)

---

## License
This project is licensed under the **MIT License** — see the `LICENSE` file for details.
