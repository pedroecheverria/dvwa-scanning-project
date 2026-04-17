# DVWA Scanning

Security scanning and analysis for Damn Vulnerable Web Application (DVWA).

## Overview

This project contains security scanning tools and scripts for testing DVWA vulnerabilities.

## Prerequisites

- Docker
- DVWA instance running
- Security scanning tools (OWASP ZAP, Nikto, etc.)

## Usage

```bash
# Start DVWA container
docker-compose up -d

```

## Scans Included

- Vulnerability scanning
- Port scanning
- SQL injection testing
- XSS detection

## Results

Scan results are stored in the `reports/` directory.