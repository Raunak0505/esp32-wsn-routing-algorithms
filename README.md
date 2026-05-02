# ESP32-Based WSN with Adaptive Routing Algorithms

## Overview
A hardware-level comparative study of Dijkstra's and Bellman-Ford 
routing algorithms implemented on an ESP32-based Wireless Sensor 
Network using the ESP-NOW protocol.

## Tech Stack
- ESP32-WROOM-32
- ESP-NOW Protocol
- DHT11 Sensors
- Blynk IoT Platform
- Arduino IDE

## Network Configurations Tested
- 4-node Star and Mesh topology
- 7-node Star and Mesh topology  
- 11-node Hybrid topology

## Key Results

| Metric | Dijkstra | Bellman-Ford |
|--------|----------|--------------|
| Convergence Time (11-node) | 18 µs | 90 µs |
| Energy Consumption (11-node) | 4.8 mJ | 23.8 mJ |
| Failure Adaptability | Moderate | High |
| Best For | Static Networks | Dynamic Networks |

## Research
Results from this project are documented in a research paper 
currently under review.

> Note: Source code is kept private as this is part of 
> an ongoing research submission.
