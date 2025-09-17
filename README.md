# Sigma Detections

A collection of Sigma rules for detecting suspicious activity across Windows, Linux, and web applications. Includes rules for:

- SSH brute force attempts
- Suspicious PowerShell execution
- Failed web application logins
- Suspicious SMB / file share access
- New Windows administrator account creation

## Overview

This repository contains Sigma rules designed for SOC monitoring, threat hunting, and incident response. Each rule includes:

- Log source information
- Detection logic
- Relevant fields for context
- Potential false positives
- Severity level

Rules are written in YAML format (`.yml`) and can be used with any Sigma-compatible SIEM or converted for specific platforms.

## Usage

1. Copy the `.yml` files into your Sigma rules directory.
2. Convert them to your SIEM’s native format using the [Sigma conversion tools](https://github.com/SigmaHQ/sigma).
3. Tune the rules based on your environment and log sources.
4. Monitor alerts and investigate any matches.
