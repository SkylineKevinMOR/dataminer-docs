---
uid: Connector_help_Skyline_Service_Definition_Basic
---

# Skyline Service Definition Basic

The basic driver for enhanced services.

## About

This driver is the basic service definition used to create enhanced services. Other enhanced services are derived from this driver.

The driver makes active alarms and subscribed elements available in the service.

Enhanced services require a DataMiner version of **9.0.3.0** or higher.

### Ranges of the driver

| **Driver Range** | **Description** | **DCF Integration** | **Cassandra Compliant** |
|------------------|-----------------|---------------------|-------------------------|
| 1.0.0.x          | Initial version | No                  | Yes (1.0.0.6+)          |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.x          | DataMiner 9.0.3.0           |

## Installation and configuration

### Creation

When editing a service, open the **Advanced** tab and select the desired **Definition**, in this case *Skyline Service Definition Basic*. Also select the desired **Version**.

### Configuration

To monitor the individual alarms in the **Active Service Alarms** table, set **Monitor Active Alarms** to *Enabled*.

## Usage

### General

The **Service Severity** displays the current alarm state of the service.

### Alarms

The **Active Service Alarms** table lists the alarms involved in this service. To enable this table, please set **Monitor Active Alarms** to *Enabled*.

### Elements

The **Service Element Status** table lists the child elements of the service and their alarm state.