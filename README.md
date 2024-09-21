# UAV_Landing_Takeoff_Control
This project explores the use of Deep Reinforcement Learning to enable autonomous landing and takeoff of unmanned aerial vehicles (UAVs) at portable vertiports. The study investigates multi-UAV coordination in dynamic environments, focusing on minimizing flight times and avoiding collisions during simultaneous landing and takeoff operations.

# UAV Autonomous Landing and Takeoff at Portable Vertiports

## Overview

This project explores the use of **Deep Reinforcement Learning** (DRL) to enable autonomous landing and takeoff of unmanned aerial vehicles (UAVs) at portable vertiports. The study investigates a novel approach for multi-UAV coordination in dynamic environments, focusing on minimizing flight times and avoiding collisions during simultaneous landing and takeoff operations.

## Table of Contents

1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Simulation Environment](#simulation-environment)
4. [Deep Reinforcement Learning Model](#deep-reinforcement-learning-model)
5. [Training and Testing](#training-and-testing)
6. [Results](#results)
7. [How to use the code](#how-to-use-the-code)

## Introduction

Unmanned aerial vehicles (UAVs) have become pivotal across numerous applications such as package delivery, remote sensing, and emergency communications. This project introduces a **portable vertiport** system, which can be deployed flexibly to reduce unnecessary energy consumption and enable continuous operations. The goal is to autonomously manage the simultaneous takeoff and landing of multiple UAVs in a constrained environment, using advanced reinforcement learning techniques.

## System Architecture

### Vertiport Model

The vertiport consists of:
- A **central spinal frame** supporting multiple cylindrical landing pads.
- **Foldable, encapsulated landing pads** to shield UAVs from adverse weather.

### UAV Model

Each UAV is represented as a sphere with predefined aerodynamic properties

## Simulation Environment

The environment is modeled in a 3D coordinate system measuring **5 × 5 × 5 meters**. It includes:
- **Multiple UAVs** initiating takeoff and landing sequences from predefined locations.
- **Non-Cooperative Entities (NCEs)** such as birds or amateur drones, which introduce dynamic obstacles.

## Deep Reinforcement Learning Model

The core of this project is a **DRL model** designed to operate in a **Markov Decision Process (MDP)** framework. Key features include:
- **Observations:** State information from UAVs and NCEs.
- **Actions:** Acceleration values optimized for collision avoidance and efficient maneuvering.
- **Rewards:** Designed to incentivize successful landings and penalize collisions or out-of-bound movements.

## Training and Testing

### Training Setup

- The model was trained using an NVIDIA GeForce GTX 3060 GPU and an Intel i7 processor.
- UAVs were trained to avoid dynamic obstacles and reach their destinations efficiently.

### Experiment Parameters

- A **grid-based positioning** strategy was used for initial placements and destinations.
- Mobile NCEs moved at a constant speed of 0.1 m/s with random destinations, mimicking real-world scenarios.

## Results

*Section to be completed based on experimental outcomes.*

## How to use the code
To be finished





