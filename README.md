# ScanThe.Net API

ScanThe.Net is an advanced threat intelligence service designed for cybersecurity professionals, researchers, and organizations seeking in-depth insights into online activities and emerging threats. 

## Overview

Our API enables users to access comprehensive data aggregated from internet-wide scans, offering invaluable context about IP addresses and related threat intelligence. With this tool, you can easily integrate advanced data analysis into your applications and security workflows.

## Features

- **Comprehensive Data Access**: Retrieve detailed results from internet-wide scans.
- **Threat Intelligence**: Gain insights into potential threats associated with specific IP addresses.
- **Real-time Analysis**: Access up-to-date information to help you make informed security decisions.

## Use Cases

- Cybersecurity analysis and reporting
- Threat hunting and investigation
- Risk assessment for organizations
- Academic research on cybersecurity trends

## JSON Structure

```json
{
  "data": [
    {
      "id": "5793882",
      "timestamp": "2024-11-17 09:40:10",
      "source_ip": "51.91.110.49",
      "source_port": "48940",
      "dest_port": "22",
      "data": "Flags [S], seq 1786990567, win 29200, options [mss 1400,sackOK,TS val 1400782606 ecr 0,nop,wscale 7], length 0",
      "autonomous_system_organization": "OVH SAS",
      "autonomous_system_number": "16276",
      "country_iso_code": "FR",
      "country_name": "France"
    },
    ...
  ],
  "metadata": {
    "fieldsDescription": {
      "id": "Unique identifier for the packet.",
      "timestamp": "Time when the packet was captured.",
      "source_ip": "IP address of the sender.",
      "source_port": "Port number of the sender.",
      "dest_port": "Port number of the receiver.",
      "data": "Data set on the packet.",
      "autonomous_system_organization": "Organization name of the autonomous system (AS) associated with the source IP.",
      "autonomous_system_number": "Number assigned to the autonomous system.",
      "country_iso_code": "ISO code of the country associated with the source IP.",
      "country_name": "Full name of the country associated with the source IP."
    }
  }
}
```
