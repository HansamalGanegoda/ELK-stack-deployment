# elk-stack-deployment
# ELK Stack Setup

This repository contains a basic setup for the ELK stack (Elasticsearch, Logstash, Kibana) using Docker.

## Purpose

The purpose of this setup is to provide a beginner-friendly environment for indexing log data and visualizing it using Kibana. This setup is ideal for understanding the basics of the ELK stack and experimenting with log analysis and visualization.

## Folder Structure

- **elk-stack/**: Contains the `docker-compose.yml` for setting up Elasticsearch, Logstash, and Kibana, as well as a sample `logstash.conf` for ingesting log files.

## Getting Started

### Prerequisites

Ensure you have Docker and Docker Compose installed on your machine.

### Steps to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/elk-stack-setup.git
   cd elk-stack-setup/elk-stack
docker-compose up
Once the stack is running, you can access Kibana in your browser at:
http://localhost:5601
