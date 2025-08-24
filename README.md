Autonomous Parrot Mini Drone Landing on Moving Platform

This project implements an autonomous landing system for the Parrot Mini Drone on a moving platform.
It was developed as part of RAS 546 – Final Project at ASU.

📂 Project Overview

The project implements:

Modeling and simulation of the Parrot Mini Drone (linear and nonlinear airframes)

Control algorithms for stable flight and autonomous landing

Vision-based detection of a moving platform

Integration with MATLAB/Simulink (MinidroneCompetition.prj) for hardware-in-the-loop testing

🗂️ Repository Structure

controller/ – Control system design and flight algorithms

mainModels/ – Main Simulink models for drone simulation

linearAirframe/ & nonlinearAirframe/ – Drone dynamics models

libraries/ – Supporting Simulink libraries

tasks/ – Individual task implementations

tests/ – Test cases and validation scripts

utilities/ – Helper scripts and utilities

resources/ & support/ – Supporting files for models and simulation

images/ – Figures and plots for documentation

⚠️ Note: The work/ directory and large .mp4 files are excluded from this repo to keep it lightweight.
You can access videos and large outputs here:
👉 Google Drive – Project Data

📄 Report

The full project documentation is available in:
📕 Final_project_report.pdf

🚀 Usage

Clone the repository:

git clone https://github.com/muditkhandelwal16/Autonomous-Parrot-mini-drone-Landing-on-Moving-Platform.git
cd Autonomous-Parrot-mini-drone-Landing-on-Moving-Platform


Open MinidroneCompetition.prj in MATLAB/Simulink.

Run the provided models in mainModels/ for simulation.

Controllers in controller/ can be modified and tested.

📹 Demonstration

Experiment videos of the drone landing are available here:
👉 Google Drive – Demo Videos
