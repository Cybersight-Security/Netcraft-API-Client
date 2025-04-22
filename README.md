<div align="center">

# Netcraft API Client

![Cybersight Security Netcraft API Client](assets/logo.png)

The Cybersight Security Netcraft API Client is a Python command-line interface that enables security professionals to interact with the Netcraft API for reporting and managing cybersecurity threats. This tool simplifies the process of submitting malicious URLs, emails, and incorrectly blocked sites to Netcraft's threat intelligence platform.

</div>

## Features:
- Report single or multiple malicious URLs
- Submit malicious email reports (with optional decryption support)
- Report incorrectly blocked URLs
- Retrieve detailed information about submitted reports
- Download files associated with threat reports
- Manage report classifications and tags
- Unsubscribe from notification emails
- Comprehensive error handling and logging

**Important Note:** This tool is designed for legitimate security research and threat reporting purposes only. All submissions to Netcraft's API should comply with applicable laws and Netcraft's terms of service.

## Data Sources

The application interacts with the following Netcraft API endpoints:

- URL submission endpoints
- Email submission endpoints
- Report management endpoints
- Tag classification endpoints
- Notification management endpoints

## Technical Implementation

### Core Components

- **Netcraft API Client (`main.py`):**
  - Handles all API interactions with Netcraft's services
  - Manages authentication and session handling
  - Processes user inputs and API responses
  - Provides comprehensive error handling

### Functionality

- **Command-Line Interface:**
  - Interactive menu-driven interface
  - Input validation and sanitization
  - Progress feedback and result display
  - Configuration management

- **Data Processing:**
  - Batch processing of URL lists
  - Email content handling
  - Report data formatting
  - File download management

## Installation and Usage

### Requirements

- Python 3.x
- `requests` library

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/cybersight/netcraft-api-client.git
   cd netcraft-api-client
   ```

2. **Install Python dependencies:**
   ```bash
   pip install requests
   ```

3. **Run the application:**
   ```bash
   python main.py
   ```

4. **Follow the on-screen instructions:**
   - Select the desired operation from the menu
   - Provide required inputs when prompted
   - View results in the console or output files

## Configuration

You can customize the following aspects of the application:

- **API Settings:** Modify default endpoints in the source code
- **Output Locations:** Change where report data is saved
- **Logging:** Adjust verbosity and log file locations
- **User Preferences:** Set default values for frequently used parameters

## License

This project is licensed under the GNU General Public License (GPL). This means you are free to:

- Use the software for any purpose
- Study how the software works and modify it
- Distribute copies
- Distribute modified versions

The full license text is included in the repository.

## About Cybersight Security

Cybersight Security is a leading provider of cybersecurity solutions, helping organizations protect their digital assets against evolving threats. Our Netcraft API Client is part of our commitment to security automation and threat intelligence sharing.

**Disclaimer:** This tool is for legitimate security research purposes only. Users are responsible for ensuring their usage complies with Netcraft's terms of service and all applicable laws. Cybersight Security makes no warranties about the completeness or accuracy of the data processed through this interface.