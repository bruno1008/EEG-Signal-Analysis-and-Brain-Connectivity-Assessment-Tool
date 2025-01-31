# EEG Signal Analysis and Brain Connectivity Assessment Tool

## Overview

This MATLAB-based software provides a sophisticated tool for analysing Electroencephalogram (EEG) signals, with a focus on extracting signal features and applying Granger causality analysis between electrodes. The software offers both qualitative and quantitative insights into brain activity and connectivity through comprehensive EEG data analysis.

## Key Features

- **Advanced Signal Processing**: Implements various filters (Alpha, Theta, Delta, Beta, Gamma) for detailed EEG signal analysis.
- **Robust Feature Extraction**: Calculates signal energy and power across different frequency bands.
- **Granger Causality Analysis**: Performs bidirectional Granger causality tests between electrodes to assess brain connectivity.
- **Flexible Parameter Adjustment**: Allows users to customise window length and overlap for precise signal analysis.
- **Multi-channel Support**: Capable of processing and analysing multiple EEG channels simultaneously.
- **Intuitive Graphical User Interface (GUI)**: User-friendly interface for seamless operation without requiring programming expertise.

## Functionality

1. **Data Import**: Efficiently loads EEG data from .mat files, extracting channel labels, EEG data, sampling frequency, and stage information.
2. **Signal Filtering**: Applies a range of frequency band filters to the EEG signals for comprehensive analysis.
3. **Energy and Power Calculation**: Computes the energy and average power of the filtered signals for each channel, stage, and frequency band.
4. **Statistical Analysis**: Conducts Granger causality tests between pairs of channels for each frequency band and stage to assess brain connectivity.
5. **Results Visualisation**: Presents results in a clear tabular format, showing power distribution across frequency bands and Granger causality test outcomes.

## User Interface

The software features an intuitive tabbed interface with two main sections:

1. **Specifics Tab**: Displays detailed EEG recording information and allows for parameter adjustment.
2. **Results Tab**: Presents comprehensive analysis outcomes in an easy-to-read table format.

## Technical Details

- Developed using MATLAB
- Utilises MATLAB's App Designer for a polished GUI creation
- Implements custom signal processing functions for advanced EEG analysis

## Contact

For any queries, support, or collaboration opportunities, please contact:

Bruno Lopes Sousa
Email: brunolopessousa23@gmail.com
