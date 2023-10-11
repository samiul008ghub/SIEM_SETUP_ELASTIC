# SIEM Setup Script for Elasticsearch, Kibana and Filebeat 

## Overview

This script automates the installation and configuration of Elasticsearch, Kibana, and Filebeat for setting up a Security Information and Event Management (SIEM) system. It guides you through the necessary steps, prompting for user input when needed.
Please note this script will not support for the versions of 8.x or above.

## Features

- **Color-coded Output:** The script provides color-coded output for better visibility.
- **Error Handling:** Comprehensive error handling to ensure a smooth setup process.
- **Logging:** Detailed logging of actions performed during the setup process.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/samiul008ghub/SIEM_SETUP_ELASTIC.git
   cd SIEM_SETUP_ELASTIC
   ```
## Run the Script:

```bash
chmod u+x siem_setup_script.sh
./siem_setup_script.sh
```
## Follow the Prompts:
The script will prompt you for necessary information and guide you through the setup process.

## Success Message:
Upon successful completion, the script will display a success message.

## Prerequisites
The script assumes a clean environment with no existing Elasticsearch, Kibana, or Filebeat installations. However, it checks for any existing installation and prompts for removal.

## Notes
Please review and customize the script based on your specific requirements.


 
 

