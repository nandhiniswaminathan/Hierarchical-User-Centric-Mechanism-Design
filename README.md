# Hierarchical-User-centric-Mechanism-Design

This project, developed as part of academic research, simulates a multi-agent system where agents interact based on predefined strategies. The simulation aims to study the dynamics of decision-making processes in a controlled environment, incorporating three types of agents: CentralAgent, IntermediaryAgent, and TargetAgent. Each agent type has unique behaviors and strategies influenced by various parameters.

Features
Central Agent: A supervisory agent that calculates overall payoffs and adjusts strategies based on the state of the system.
Intermediary Agents: Agents that choose between passive and intervention strategies based on the behavior of target agents.
Target Agents: Agents that choose between compliance and defiance based on the strategies of intermediary agents and their own payoffs.

Usage
To run the simulation, execute the main script:
python simulation_script.py

The script will run the simulation for a predefined number of steps and output the behavior of agents at each step along with visualizations of their strategies and levels over time.

Simulation Details
The simulation runs for a specified number of iterations.
Agents' actions and strategies are determined by predefined rules and payoff calculations.
The simulation outputs detailed logs and plots showing the evolution of agents' strategies and levels.

License
This project is licensed under the MIT License.

