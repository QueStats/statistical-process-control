# Statistical Process Control & Capability Analysis

Analysis of manufacturing process stability and capability using statistical process control methods in R.

## Overview

This project evaluates the stability and capability of a manufacturing process using control charts and capability metrics.

The dataset contains:

• 722 production observations  
• 52 process subgroups  

## Methods

Statistical techniques used:

• X̄ (X-bar) control charts  
• S control charts  
• Process capability indices (Cp, Cpk)  
• Estimation of process mean and standard deviation

## Results

Estimated parameters:

μ = 15.06  
σ ≈ 4.00  

Process capability:

Cp = 0.208  
Cpk = 0.13  

Results indicate the process is **not capable**, with more than 50% of units outside specification limits.

## Repository Structure

analysis/ – R Markdown source code  
data/ – dataset used in analysis  
report/ – compiled project report
