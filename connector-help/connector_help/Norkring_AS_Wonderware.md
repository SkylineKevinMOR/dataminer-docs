---
uid: Connector_help_Norkring_AS_Wonderware
---

# Norkring AS Wonderware

This protocol will interface with the **Wonderware** device, receiving information from the device via **SNMP**.

## About

This driver allows the user to add and remove stations from a configuration table.

It will export different drivers based on the information present in the Station Table. A list of possible exported drivers can be found in the section 'Exported Drivers'.

### Ranges of the driver

| **Driver Range** | **Description** |
|------------------|-----------------|
| 1.0.0.x          | Initial version |

### Exported Drivers

| **Exported Protocol**            | **Description**            |
|----------------------------------|----------------------------|
| Norkring AS Wonderware Type1 DVE | Driver for Type1 Stations  |
| Norkring AS Wonderware Type2 DVE | Driver for Type 2 Stations |

## Installation and configuration

### Creation

#### SNMP connection

This driver uses a Simple Network Management Protocol (SNMP) connection and requires the following input during element creation:

SNMP CONNECTION:

- **IP address/host**: The polling IP of the device.

SNMP Settings:

- **Port number**: The port of the connected device, by default *161*.
- **Get community string**: The community string used when reading values from the device, by default *public*.
- **Set community string**: The community string used when setting values on the device, by default *private.*

### Configuration

The Station Table will be loaded with default values. These values should be updated in case there are any changes to the device/station OIDs and types.

## Usage

### System

This page displays a configurable table, which has a context menu and allows you to configure which **OID**, **Station Name** and **Station Type** each different station will have. The OID value is the number associated with each station. The station name will determine the name of the corresponding exported DVE element (with the parent element name as a prefix). You can also import or export this table to an Excel file.

The **System Info** page button displays specific information regarding this manager device, such as the **System Description**, **Object ID**, **Up Time**, **Contact**, **Name** and **Location**.

## DataMiner Connectivity Framework

This device does not contain any DCF implementation.