# Jua Kali Miner

Jua Kali is an open-source project designed to run Bitcoin ASIC hashboards on direct DC power, such as from solar panels or batteries. This project provides the necessary hardware and software to create a more resilient and off-grid Bitcoin mining setup. This repository serves as the main entry point for the Jua Kali project, containing the hardware specifications and the software source code.

## About the Project

The Jua Kali Miner was born from the vision of enabling Bitcoin mining in unconventional scenarios, free from reliance on traditional AC power grids. This developer release showcases the successful operation of M30s hashboards using an ePIC UMC control board, all powered directly from a DC source. This setup is ideal for hobbyists, off-grid communities, and anyone interested in sustainable and decentralized mining.

## Features

- **Direct DC Power:** Run ASIC hashboards directly from DC power sources like solar panels or batteries, eliminating the need for AC-DC power supplies.
- **Modular Design:** The system is composed of distinct hardware and software components, allowing for flexibility and customization.
- **Open Source:** All hardware and software designs are open source, encouraging community contributions and innovation.
- **Web-Based Monitoring:** A user-friendly web interface provides real-time monitoring of your miner's performance.

## Project Structure

This repository is organized into two main sections:

- [**Hardware**](./Hardware/): Contains all the information related to the physical components of the Jua Kali Miner. This includes:
  - Wiring diagrams
  - Bill of Materials (BOM)
  - Assembly instructions
- [**Code**](./Code/): Contains the source code for the software that runs the Jua Kali Miner. This includes:
  - Arduino firmware for sensor readings
  - Go services for data processing and control
  - A React-based web interface for monitoring

## Getting Started

To build your own Jua Kali Miner, you will need to assemble the hardware and set up the software.

1.  **Hardware Assembly:** Start by visiting the [Hardware](./Hardware/) directory for detailed instructions on the necessary components and how to assemble them.

2.  **Software Setup:** Once the hardware is assembled, head over to the [Code](./Code/) directory for instructions on how to set up the software on your Raspberry Pi and Arduino.

## Contributing

We welcome contributions from the community! If you are interested in improving the Jua Kali Miner, please feel free to fork the repository, make your changes, and submit a pull request. You can also open an issue to report bugs or suggest new features.

## License

The Jua Kali Miner project is licensed under the [GNU General Public License v3.0](./LICENSE).

