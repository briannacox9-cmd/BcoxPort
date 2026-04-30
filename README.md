# Brianna Cox — DevOps / Platform Engineering Portfolio

## Overview

This repository showcases a hands-on platform engineering portfolio focused on observability, automation, Linux security, and AI-enabled microservices.

The goal of this portfolio is to demonstrate production-style engineering practices, including monitoring, alerting, troubleshooting, secure configuration, automation, and scalable API design.

## Core Focus Areas

- Observability and monitoring
- Linux systems administration
- DevOps automation
- Platform reliability
- AI microservice development
- Security and compliance-minded operations

## Projects Included

## 1. Observability Stack

### Summary

Built a Linux-based monitoring stack using Prometheus, Grafana, Node Exporter, and Alertmanager to simulate production observability workflows.

### Technologies

- Prometheus
- Grafana
- Node Exporter
- Alertmanager
- Linux
- systemd
- FirewallD
- YAML configuration

### Work Completed

- Installed and configured Prometheus
- Configured Node Exporter for system metrics
- Built Grafana dashboards for system health
- Configured firewall access for monitoring ports
- Troubleshot Prometheus YAML configuration errors
- Validated services using systemd, curl, and port checks

### Skills Demonstrated

- Monitoring and observability
- Metrics collection
- Dashboard design
- Linux service troubleshooting
- Alerting fundamentals
- Root cause analysis

## 2. AI Sponsorship SaaS Microservice

### Summary

Built a FastAPI microservice prototype that generates structured sponsorship draft recommendations using either AI logic or deterministic fallback logic.

### Technologies

- Python
- FastAPI
- Uvicorn
- OpenAI API
- REST API
- Swagger UI
- WSL2 Ubuntu
- Environment variables

### Key Features

- POST API endpoint for sponsorship draft generation
- Feature flag for enabling or disabling AI
- Structured JSON response
- Fallback logic for demo and offline use
- Logging for request visibility
- API documentation through Swagger UI

### Example Endpoint

```bash
POST /sponsorships/draft
