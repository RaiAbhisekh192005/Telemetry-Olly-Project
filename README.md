# Telemetry-Olly0-Project

🚀 **Telemetry-Olly0-Project** is an advanced observability project utilizing the OpenTelemetry Demo Application in a DevOps environment. This project demonstrates how to deploy, monitor, and trace an application using AWS, Docker, Grafana, Jaeger UI, and Load Generator UI.

## Project Overview

Telemetry-Olly0-Project is designed to explore and implement modern observability practices in a cloud-based DevOps environment. The project showcases the deployment of the OpenTelemetry Demo Application, leveraging tools like AWS, Docker, Grafana, and Jaeger for comprehensive monitoring and tracing.

## Architecture Diagram

The architecture of the Telemetry-Olly0-Project is illustrated below:

![Architecture Diagram](https://github.com/user-attachments/assets/78fc1493-a546-4d64-9f68-4f9d1674692c)

_Description_: The diagram provides an overview of the deployment and observability stack, including how AWS, Docker, OpenTelemetry, Grafana, Jaeger, and the Load Generator UI are interconnected to monitor and trace the application.

## Features

- **Deployment**: Utilizes AWS and Docker to deploy the OpenTelemetry Demo Application.
- **Monitoring**: Integrates Grafana for real-time monitoring of application performance and health.
- **Tracing**: Implements Jaeger UI for distributed tracing and Load Generator UI for testing system performance.
- **Observability**: Provides insights into application behavior and system performance through advanced observability techniques.

## Tech Stack

- **AWS**: Cloud infrastructure for deploying the application.
- **Docker**: Containerization platform for packaging and running the application.
- **OpenTelemetry**: Framework for generating and collecting telemetry data.
- **Grafana**: Monitoring tool for visualizing metrics and logs.
- **Jaeger**: Distributed tracing system for monitoring and troubleshooting.
- **Load Generator UI**: Tool for generating load to test application performance.

## Prerequisites

- AWS EC2 instance (xlarge)
- SSH access to the instance

## Step 1: Update and Upgrade the System

First, update and upgrade the system packages:

```bash
sudo apt update && sudo apt upgrade -y

