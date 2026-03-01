# Cloud-Native Infrastructure Monitoring & Alerting System

## Overview

This project simulates a production-ready cloud-native infrastructure monitoring setup using AWS EC2 and CloudWatch.

The goal was to understand observability, monitoring, alerting, and reliability engineering principles in distributed cloud environments.

---

## Architecture

- AWS EC2 Instance (Linux)
- CloudWatch Metrics & Logs
- CloudWatch Alarms
- Basic automated alerting
- Shell-based provisioning

---

## Features

- Provisioned EC2 instance running Linux
- Configured CloudWatch agent for system metrics
- Monitored CPU, memory, and network utilization
- Implemented alert mechanisms for high CPU usage
- Enabled centralized logging for operational visibility

---

## Technologies Used

- AWS EC2
- AWS CloudWatch
- Linux
- Shell Scripting
- Basic Infrastructure Monitoring
- Logging & Observability Concepts

---

## Setup Instructions

### 1. Launch EC2 Instance
- Amazon Linux 2
- Enable CloudWatch permissions via IAM role

### 2. Install CloudWatch Agent
```bash
sudo yum install amazon-cloudwatch-agent
