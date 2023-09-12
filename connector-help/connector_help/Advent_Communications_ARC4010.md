---
uid: Connector_help_Advent_Communications_ARC4010
---

# Advent Communications ARC4010

The **ARC4010** is a redundancy controller capable of monitoring the status of 10 units and controlling 10 wave guide.

## About

The driver is using a **serial connection** to communicate with the device.

### Ranges of the driver

| **Driver Range** | **Description** | **DCF Integration** | **Cassandra Compliant** |
|------------------|-----------------|---------------------|-------------------------|
| 1.0.0.x          | Initial version | No                  | Yes                     |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.x          | A.19                        |

## Installation and configuration

### Creation

#### Serial \[Main\] connection

This driver uses a serial connection and requires the following input during element creation:

SERIAL CONNECTION:

- Direct connection:

- **Baudrate**: 9600
  - **Databits**: 8
  - **Stopbits**: 1
  - **Parity**: No
  - **FlowControl**: No

- Interface connection:

- **IP address/host**: \[The polling IP of the device.\]
  - **IP port**: \[The IP port of the device. Indicate if required or not. If so, specify default value and range.\]
  - **Bus address**: 0

## Usage

### General

Here you find some general parameters about the device like; Serial Number, Software Revision, Model ID.

### Status

Here you find all the parameters about the statuses of the units and the device.

- Switch Positions
- Unit statuses
- Faults
- Alarm
- Protection
- Mode

There is a button with device information.

### Configuration

At this page you can set some parameters from the device.

- Switch Positions
- Protection
- Lock Mode

There is a button where you can change the chain prioritys.