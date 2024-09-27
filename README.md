# Online Calculator for Wireless and Mobile Networks

This project provides an **online calculator** to assist with critical network design calculations for wireless and mobile networks. It includes calculators for various network parameters such as samplers, encoders, interleavers, resource elements, OFDM symbols, power transmission, and throughput. The project was developed as part of the **Wireless and Mobile Networks** course (ENCS5323), with a focus on simplifying complex calculations for both educational and practical applications.

## Project Overview

This calculator provides five key functionalities:
1. **Wireless Communication Calculator** – Calculates the number of bits and rates for samplers, quantizers, source encoders, channel encoders, and interleavers.
2. **LTE Resource Block Calculator** – Calculates the number of bits and rates for resource elements, OFDM symbols, resource blocks, and maximum transmission via parallel resource blocks.
3. **Transmit Power Calculator** – Computes the transmitted power based on the transmitter and receiver specifications in a flat environment.
4. **Throughput Calculator** – Calculates the throughput percentage for different multiple access techniques.
5. **Cellular System Calculator** – Assists in designing cellular systems with inputs such as the number of subscribers, traffic load, and other parameters.

## Features

### 1. **Wireless Communication Calculator**
   - **Inputs**:
     - Signal Bandwidth (KHz)
     - Quantizer Bits
     - Source Encoder Composition Rate
     - Channel Encoder Rate
     - Interleaver Bits
   - **Outputs**:
     - Sampling Frequency
     - Quantization Levels
     - Bit Rate at the Output of the Source Encoder
     - Bit Rate at the Output of the Channel Encoder
     - Bit Rate at the Output of the Interleaver

### 2. **LTE Resource Block Calculator**
   - **Inputs**:
     - Resource Block Bandwidth (KHz)
     - Subcarrier Spacing (KHz)
     - Number of OFDM Symbols per Resource Block
     - Modulation Type
     - Number of Parallel Resource Blocks
   - **Outputs**:
     - Number of Bits per Resource Element
     - Number of Bits per OFDM Symbol
     - Number of Bits per Resource Block
     - Maximum Transmission Rate

### 3. **Transmit Power Calculator**
   - **Inputs**:
     - Path Loss
     - Frequency (MHz)
     - Antenna Gain (Transmitter & Receiver)
     - Transmitter/Receiver Amplifier Gain
     - Noise Figure, Noise Temperature
     - Link Margin, BER, Modulation Type
   - **Outputs**:
     - Transmit Power in Watts and dBm

### 4. **Throughput Calculator**
   - **Inputs**:
     - Data Transmission Bandwidth
     - Frame Size and Rate
     - Maximum Signal Propagation Time
   - **Outputs**:
     - Throughput Percentage (S = G * e^(-2G))

### 5. **Cellular System Calculator**
   - **Inputs**:
     - City Area, Number of Subscribers
     - Average Calls per Subscriber per Day
     - Call Duration, Blocking Probability, Number of Channels
     - Path Loss Exponent, Receiver Sensitivity
   - **Outputs**:
     - Maximum Distance Between Transmitter and Receiver
     - Cell Size, Number of Cells in Service Area
     - Traffic Load in the Entire Cellular System
     - Traffic Load per Cell, Blocking Probability

## User Interface

The calculator's web interface is designed with five buttons on the main page. Each button redirects the user to a specific calculator based on the selected task. The interface includes input fields for parameters and displays the computed results.

### Pages:
1. **Main Page**: Contains navigation buttons to all calculators.
2. **Wireless Communication Calculator Page**
3. **LTE Resource Block Calculator Page**
4. **Transmit Power Calculator Page**
5. **Throughput Calculator Page**
6. **Cellular System Calculator Page**

## Test Cases

We have included a set of test cases for each calculator to ensure accurate functionality and validate the outputs:

- **Wireless Communication Calculator Test**
- **LTE Resource Block Calculator Test**
- **Transmit Power Calculator Test**
- **Throughput Calculator Test**
- **Cellular System Calculator Test**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-calculator-wireless-mobile-networks.git
   cd online-calculator-wireless-mobile-networks
