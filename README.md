﻿# CI_Pipeline_GitActions_DevOps_HW4

This repository demonstrates a Continuous Integration (CI) pipeline using GitHub Actions and DevOps practices. It primarily uses Docker and Python to automate building, testing, and deploying applications.

## Features

- GitHub Actions workflow for CI/CD
- Docker integration for containerized builds and deployments
- Python scripts or applications as core components

## Getting Started

### Prerequisites

- Docker installed on your system
- Python (version 3.x recommended)
- A GitHub account

### Setup

1. Clone this repository:
    ```bash
    git clone https://github.com/AyaanKhan1576/CI_Pipeline_GitActions_DevOps_HW4.git
    cd CI_Pipeline_GitActions_DevOps_HW4
    ```

2. Build the Docker image:
    ```bash
    docker build -t ci_pipeline_hw4 .
    ```

3. Run the Docker container:
    ```bash
    docker run ci_pipeline_hw4
    ```

4. (Optional) Install dependencies for Python locally:
    ```bash
    pip install -r requirements.txt
    ```

## GitHub Actions

This repository utilizes GitHub Actions for automating the build and test process. Workflow files can be found in the `.github/workflows/` directory.
