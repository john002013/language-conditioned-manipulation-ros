# language-conditioned-manipulation-ros
A ROS 2–based pick-and-place robotic system integrating MoveIt, LangChain agentic AI, and Gazebo Ignition for language-conditioned manipulation.
Overview

This repository presents a ROS 2–based pick-and-place robotic system capable of executing natural language commands to manipulate objects in a simulated environment. The system integrates agentic AI (LangChain) with robot perception and motion planning (MoveIt 2), enabling language-to-action control for autonomous manipulation tasks.

The robot is designed to identify a box and place it into a target container (bucket) within a constrained workspace, demonstrating embodied AI, robot perception, and language-conditioned autonomy.

# System Architecture

The system follows a modular, agent-based architecture:

## Language Interface:
Natural language commands are interpreted using an LLM-driven agentic framework (LangChain).

## Decision & Task Planning:
The agent decomposes high-level commands into executable robotic actions.

## Motion Planning:
MoveIt 2 is used for collision-aware motion planning and manipulation.

## Simulation Environment:
Gazebo Ignition provides physics-based simulation and environment interaction.

Control Framework:
ROS 2 handles node communication, execution, and system integration.

# Key Features

Natural language–driven robotic manipulation

Agentic AI–based task reasoning and execution

Collision-aware pick-and-place using MoveIt 2

ROS 2 modular node architecture

Gazebo Ignition simulation for safe testing and validation

# Technologies Used

ROS 2

MoveIt 2 (motion planning and manipulation)

LangChain (agentic AI framework)

Gazebo Ignition (robot simulation)

Python / C++ (ROS nodes and AI integration)

# Use Case

This project demonstrates how large language models can be embedded into robotic systems to enable intuitive human–robot interaction, with applications in:

Intelligent manipulation systems

Human–robot interaction (HRI)

Embodied and agent-based AI

Autonomous service and industrial robots

Research Relevance

The system serves as a practical exploration of:

Language-conditioned robot control

Embodied AI for real-world manipulation

Agent-based architectures in autonomous systems

It is suitable for academic research, prototyping and educational purposes.
