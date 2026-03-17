# FCIS - Graduation Project - Multi-Class and Real-Time Violence Detection in CCTV using Deep Learning Techniques

## Summary

## Academic Information

## Table of Contents

## Installation and Environment Setup

## Problem Introduction

## Problem Description

Given Training Dataset  

## Problem Requirements

1. Dataset Requirements
    - Diversity
        - Different locations (streets, intersections, neighborhoods, etc.)
        - Different times of day (day, night, dawn, dusk)
        - Different Weather (sunny, rain)
    - Camera Setup
        - Footage must be captured from fixed CCTV cameras (non-moving) 
    - Dataset Size
        - At least 1000 videos per class 
    - Clip Duration
        - Each clip: 2-5 seconds
    - Single-label Classification
        - Each clip footage must contain only one class
    - Environment Constraint
        - Only outdoor street scenes (no indoor footage)
    - Balanced Classes
        - Equal number of samples across all classes
    - Motion Presence
        - Clips should contain meaningful activity, No empty/static scenes

2. Multi-Class
    - Safe/Normal (running, walking, moving cars, hugging, etc.)
    - Fighting (kicking, punching, choking, hitting with object, etc.)
    - Vehicle Accidents (vehicle-vehicle, vehicle-human, vehicle-environment)
    - Weapons (Guns, Knives, shooting)
    - Camera Tampering (vandalism, Defocus, spray, covering)
    - Dangerous Signs (heavy smoke, explosion, fire)

3. Real-Time 
    - Lightweight architecture
    - Low Latency
    - Sliding Window Processing
        - Predictions are made using consecutive frames (2–5 seconds window)

4. Alerting and Control System
    - Web-Based Interface
    - Live-Monitoring Dashboard
    - Automatic Alert Generation
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