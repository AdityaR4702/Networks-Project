# Python Code for Network Simulation, Economic Growth, and Shock Recovery

This directory contains the Python code for simulating and analyzing an economic network over time, including economic growth, shocks, and recovery. The project models economic agents (nodes) within a network, simulating growth and shocks over a series of periods, and evaluates the impact of these shocks using clustering coefficients.

## Folder Structure

- **1_basic_network_creation.py**: Creates the initial network structure. This file defines the basic network, representing economic agents as nodes and their interconnections as edges. It provides the foundation for the network that will be used in further simulations.

- **2_random_iterations.py**: This script runs random iterations for 30 periods to simulate network evolution over time. It updates the network based on random fluctuations in the connections between nodes.

- **3_economic_growth.py**: Replaces the random iterations with a more structured economic growth model. This script simulates economic growth at a fixed rate (2%) with fluctuations over the 30-year period, adjusting the network accordingly.

- **4_introducing_shock.py**: Introduces an economic shock at a specific time point (e.g., year 18). This file models how the network and its nodes are impacted by the shock, disrupting their connections and economic performance.

- **5_shock_and_recovery.py**: Expands on the previous script by modeling the recovery process after the shock. This file tracks how the network and its economic agents recover over time, including the timeline and mechanisms of recovery.

- **6_clustering_coefficient.py**: Calculates and analyzes the clustering coefficient of the network over time. This script is used to evaluate how the shock and recovery affect the network's structure and cohesion, with a focus on clustering patterns.

## Key Components

1. **Network Creation**:
   - The initial network structure is created with random or predefined connections between nodes. This forms the backbone of the simulation.

2. **Random Iterations**:
   - For 30 periods, random changes in the network's connections simulate fluctuations in the economy. This is used to test network dynamics under uncertainty.

3. **Economic Growth**:
   - Instead of random iterations, this approach simulates an economy with a consistent growth rate (2%) and incorporates fluctuations to reflect real-world economic variability.

4. **Introducing a Shock**:
   - A shock is introduced at year 18, disrupting the network. The shock may affect the economic performance and connectivity of the network’s nodes.

5. **Shock and Recovery**:
   - After the shock, the recovery process is simulated, tracking how the network regains its previous performance and structure. This helps to understand resilience and recovery in economic systems.

6. **Clustering Coefficient**:
   - The clustering coefficient of the network is computed over time to assess how the shock and recovery affect network cohesion. A high clustering coefficient indicates that nodes tend to cluster together, which may affect how quickly the network recovers after a shock.

## Usage

### Prerequisites

Ensure that you have Python 3.x installed, along with the necessary libraries. You can install them by running:

```bash
pip install -r requirements.txt
