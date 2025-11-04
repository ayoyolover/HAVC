# Hierarchical Federated Learning HVAC Control System (HFL-HVAC)

## System Overview

This project implements an intelligent HVAC control system based on Hierarchical Federated Learning (HFL) and Deep Reinforcement Learning (DRL). The system adopts a three-tier architecture (Device-Edge-Cloud) to achieve privacy-preserving distributed learning and intelligent energy-saving control.

## Core Features

### 1. Three-Tier Architecture Design

- **Device Tier**: Local data collection, preprocessing, and model training
- **Edge Computing Tier**: Device clustering, local model aggregation, and personalized learning
- **Cloud Center Tier**: Global aggregation, DRL decision-making, and system optimization

### 2. Federated Learning Capabilities

- Supports multiple aggregation algorithms (FedAvg, FedProx, SCAFFOLD, FedNova)
- Personalized Federated Learning (FedPer, Ditto)
- Cluster-based hierarchical aggregation

### 3. Privacy Protection Mechanisms

- Local Differential Privacy (LDP)
- Gradient clipping and noise addition
- Secure aggregation protocols
- Data anonymization

### 4. DRL Intelligent Control

- Soft Actor-Critic (SAC) algorithm
- Multi-objective optimization (comfort, energy consumption, peak shaving)
- Adaptive control strategies

### 5. Simulation Environment

- Complete building thermodynamic model
- Multi-zone HVAC system simulation
- Weather and occupancy simulation
- Time-of-use electricity pricing consideration

## The codebase is currently being organized and will be open-sourced in the future.

