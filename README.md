# High-Speed Device Frequency Characterisation Demo

## Overview

This repository presents a sanitised portfolio version of a high-speed optoelectronic device frequency characterisation project. The original project involved RF and optical measurement, frequency response analysis, calibration and de-embedding for high-speed photonic devices.

Due to confidentiality considerations, this repository does not include original device information, raw measurement data, detailed experimental setup parameters or unpublished results. Instead, it demonstrates the general measurement workflow, data analysis methods and technical skills involved in high-frequency device characterisation.

## Repository Structure

```text
high-speed-optoelectronic-device-characterisation-demo/
│
├── README.md
│
├── figures/
    ├── deembedding_ADS_simulation_system.png
    ├── S-parameter_example-MZM.png
    ├── deembedding_example-PD.png
    └── VNA_S-parameter_concept.png

Codes and data sheets are not provided in this Demo
```

## Project Background

High-speed optoelectronic devices require accurate frequency response characterisation to evaluate their performance in optical communication, photonic integrated circuits and high-speed sensing systems. However, measured RF responses can be affected by cables, probes, connectors, pads and other parasitic effects in the measurement system.

To recover the intrinsic response of the device under test, calibration and de-embedding methods are commonly applied. This project focuses on the workflow for analysing measured frequency response data and separating device behaviour from measurement-system artefacts.

## Objectives

* Analyse frequency response data of high-speed optoelectronic devices.
* Understand the influence of RF probes, ports and parasitic structures on measured responses.
* Apply calibration and de-embedding concepts to improve measurement accuracy.
* Extract useful performance indicators from frequency-domain data.
* Present a clean and reproducible data-processing workflow using simplified example data.

## Methods

### 1. Frequency Response Measurement

The original project involved high-frequency characterisation using RF and optical measurement equipment. The device response was measured in the frequency domain and analysed to evaluate bandwidth-related performance.

### 2. Calibration Workflow

A calibration procedure was used to reduce systematic errors introduced by the measurement system. This step is essential for improving the reliability of high-frequency response measurements.

### 3. De-Embedding Concept

The measured response contains contributions from both the device under test and the surrounding measurement structures. De-embedding was applied conceptually to reduce the influence of parasitic RF responses and recover a closer approximation of the intrinsic device response.

### 4. Data Analysis

The analysis workflow includes reading frequency-domain data, plotting S-parameter-like responses, comparing raw and corrected curves, and extracting characteristic bandwidth information.

## Demonstration Content

This public repository contains only simplified or synthetic data for demonstration purposes. The scripts are designed to show the data-processing workflow rather than reproduce confidential experimental results.

Example tasks include:

* Plotting frequency response curves
* Comparing raw and corrected response data
* Extracting approximate bandwidth metrics
* Demonstrating a simplified de-embedding workflow
* Visualising frequency-domain measurement trends

## Tools and Techniques

* Python
* MATLAB
* NumPy
* Matplotlib
* Frequency-domain data analysis
* S-parameter-style response plotting
* Calibration and de-embedding concepts
* High-speed optoelectronic device characterisation

## Example Workflow

```text
Raw frequency response data
        ↓
Calibration / reference correction
        ↓
Parasitic response removal
        ↓
Intrinsic response estimation
        ↓
Bandwidth and performance analysis
```

## Confidentiality Notice

This repository is a simplified and anonymised portfolio version of the original project. It does not contain confidential device structures, raw experimental data, internal measurement files, unpublished results or detailed setup parameters. All sample data and figures are either synthetic, simplified or prepared for demonstration purposes only.

## Keywords

High-speed optoelectronics, frequency response, S-parameters, RF measurement, calibration, de-embedding, photonic device characterisation, bandwidth analysis, Python, MATLAB.
