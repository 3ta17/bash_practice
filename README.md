# Scripts Ptactice

This repository contains a collection of useful scripts designed to simplify system administration and automation tasks. Each script serves a specific purpose, ranging from network diagnostics to generating random passwords.

---

## Repository Structure

- **`backup-rhevm`**: Automates the backup of Red Hat Enterprise Virtualization Manager (RHEV-M) environments.
- **`convert-nic-to-bonded`**: Converts standalone network interfaces into bonded interfaces for redundancy and performance.
- **`email-when-up`**: Sends an email notification when a specified system or service becomes available.
- **`generate-random-password`**: Generates secure random passwords for various use cases.
- **`ping-host`**: Checks the availability of a host by sending periodic ping requests.
- **`prettify-multipath`**: Formats and displays multipath storage configurations for easier interpretation.
- **`show-cmdb-info`**: Retrieves and displays Configuration Management Database (CMDB) information.
- **`show-disk-space-used-by-vg`**: Shows the disk space usage for specific volume groups.
- **`show-io-scheduler`**: Displays the current I/O scheduler for system disks.
- **`show-network-port-info`**: Provides detailed information about network ports.
- **`show-total-disk-space-used`**: Summarizes the total disk space used across the system.
- **`show-wwpns`**: Lists World Wide Port Names (WWPNs) for connected Fibre Channel devices.
- **`tail-db2diag`**: Tails the DB2 diagnostic log for real-time monitoring.
- **`touch-test`**: Creates temporary test files for system diagnostics or testing.

---

## Prerequisites

Before using the scripts, ensure the following:
- Python 3.x or Bash installed (depending on the script).
- Required libraries or dependencies for specific scripts (e.g., `email-when-up` may require `mailutils` or similar packages).
- Administrative privileges for scripts that modify system configurations.

---

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   cd Real-World-Scripts
