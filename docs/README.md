# 🚀 AI-Powered Solar Flare Forecasting & Satellite Protection System

## Bharatiya Antariksh Hackathon 2026

### Problem Statement 15
Forecasting and/or Nowcasting of Solar Flares using combined Soft and Hard X-ray data from Aditya-L1.

---

## Project Overview

Solar flares are sudden bursts of energy released from the Sun that can disrupt satellite communications, GPS navigation, and power systems.

This project proposes an AI-powered early warning system that combines SoLEXS (Soft X-Ray) and HEL1OS (Hard X-Ray) observations from Aditya-L1 to forecast solar flares and automatically trigger satellite protection mechanisms.

---

## Objective

- Detect solar flares using Soft and Hard X-Ray data
- Forecast flare occurrence before the event
- Generate real-time risk levels
- Trigger satellite safe-mode operations
- Improve space-weather preparedness

---

## System Architecture

Aditya-L1 Data (SoLEXS + HEL1OS)

↓

Feature Extraction

↓

Transformer-Based Forecasting Model

↓

Risk Prediction Engine

↓

risk_output.csv

↓

Satellite Protection Logic

↓

SAFE MODE ACTIVATION

---

## Team Roles

### EEE1
- Solar Physics Analysis
- Feature Extraction
- Data Understanding

### CSD1
- AI/ML Model Development
- Transformer Training
- Forecasting Logic

### CSD2
- Prediction Engine
- Risk Assessment
- Output Generation

### EEE2
- Satellite Response Logic
- MATLAB / Stateflow Simulation
- Safe Mode Activation

---

## Expected Output

Example:

Risk Level : HIGH

Flare Probability : 87%

Satellite Status : SAFE MODE ACTIVATED

---

## Impact

The proposed system enables early warning of solar flare events and supports autonomous satellite protection, reducing operational risks caused by severe space-weather conditions.

---

## Technologies Used

- Python
- Machine Learning
- Transformer Models
- Aditya-L1 Data
- MATLAB
- Stateflow
- GitHub

---

## Project Workflow

EEE1 → Solar Features

↓

CSD1 → AI Forecasting

↓

CSD2 → Risk Prediction Engine

↓

EEE2 → Satellite Protection Logic

↓

Satellite Safe Mode

---

## Future Scope

- Real-time integration with Aditya-L1 streams
- Multi-class flare forecasting
- Autonomous spacecraft health management
- Advanced space-weather monitoring systems
