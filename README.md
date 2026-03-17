# FCIS - Graduation Project - Multi-Class and Real-Time Violence Detection in CCTV using Deep Learning Techniques

## Summary

## Academic Information

## Table of Contents

## Installation and Environment Setup

## Problem Introduction

## Problem Description

Given Training Dataset  

## Problem Requirements

- Dataset Requirements
    1. Diversity
        - Different locations (streets, intersections, neighborhoods, etc.)
        - Different times of day (day, night, dawn, dusk)
        - Different Weather (sunny, rain)
    2. Camera Setup
        - Footage must be captured from fixed CCTV cameras (non-moving) 
    3. Dataset Size
        - At least 1000 videos per class 
    4. Clip Duration
        - Each clip: 2-5 seconds
    5. Single-label Classification
        - Each clip footage must contain only one class
    6. Environment Constraint
        - Only outdoor street scenes (no indoor footage)
    7. Balanced Classes
        - Equal number of samples across all classes
    8. Motion Presence
        - Clips should contain meaningful activity, No empty/static scenes

- Multi-Class
    1. Safe/Normal (running, walking, moving cars, hugging, etc.)
    2. Fighting (kicking, punching, choking, hitting with object, etc.)
    3. Vehicle Accidents (vehicle-vehicle, vehicle-human, vehicle-environment)
    4. Weapons (Guns, Knives, shooting)
    5. Camera Tampering (vandalism, Defocus, spray, covering)
    6. Dangerous Signs (heavy smoke, explosion, fire)

- Real-Time 
    1. Lightweight architecture
    2. Low Latency
    3. Sliding Window Processing
        - Predictions are made using consecutive frames (2–5 seconds window)

- Alerting and Control System
    1. Web-Based Interface
    2. Live-Monitoring Dashboard
    3. Automatic Alert Generation
        - Time and Date
        - Location
        - Detected Class
        - Short video clip of the event for Evidence 
        - Confidence Score (%)

## System Architecture and Design 


## Input


## Output


## Algorithms


## Evaluation Metrics / Performance


## References and Academic Papers