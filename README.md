# Learning Platform

## Project Description

Learning Platform is a modern educational platform based on Moodle, managed using Terraform, and hosted on AWS. The project aims to create a scalable and secure environment for online learning.

## Technologies

- **Moodle**: Learning Management System (LMS) used for creating online courses.
- **Terraform**: Infrastructure as Code (IaC) tool used for automating deployments on AWS.
- **AWS (Amazon Web Services)**: Cloud computing platform where the platform is hosted.

## Requirements

- AWS account
- Installed Terraform
- Installed Moodle

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repository/learning-platform.git
    cd learning-platform
    ```

2. **Configure Terraform**:
    - Configure your AWS credentials.
    - Update the Terraform configuration files (`main.tf`, `variables.tf`) as needed.

3. **Deploy the infrastructure**:
    ```bash
    terraform init
    terraform apply
    ```

4. **Install Moodle**:
    - After deploying the infrastructure, log in to the server and install Moodle according to the official documentation.

## Project Structure

- `terraform/`: Terraform configuration files.
- `moodle/`: Moodle configuration files and installation scripts.
- `docs/`: Project documentation.

## Usage

1. **Log in to Moodle**:
    - Open your browser and navigate to the URL of your Moodle instance.
    - Log in using the admin credentials.

2. **Create courses**:
    - After logging in, go to the administration section and start creating courses.

## Contribution

If you want to contribute to the project, please report issues and propose improvements using the GitHub issue tracker.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
