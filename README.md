# Mini Project - Creating AWS Resources with Functions & Introducing Arrays

## Project Overview
This 2-hour mini-project automates AWS resource creation (EC2 instances and S3 buckets) using shell scripting functions and arrays for DataWise Solutions, executed on Ubuntu (WSL) with VS Code via Ubuntu.

## Setup
- Initiated on Jul 02, 2025, 10:01 AM WAT.
- Used Ubuntu terminal (WSL) with VS Code, documented in ~/Documents/Workspace/Shell_AWS_Mini_Project.

## Project Execution
- **Script Development**: Updated `aws_resources.sh` with `create_ec2_instances` and `create_s3_buckets` functions, using arrays for S3 bucket names and error handling with `$?`.
- **Testing**: Ran script to create 2 EC2 instances and 5 S3 buckets (e.g., `datawise-Marketing-Data-Bucket`), verified in AWS console (region `eu-west-2`).

## Learning Summary
In this mini project, I deepened my understanding of shell scripting by integrating it with AWS resource provisioning. I learned to create modular functions like `create_ec2_instances` and `create_s3_buckets` to automate EC2 and S3 bucket setup, enhancing code reusability and maintainability. I explored arrays to efficiently manage multiple S3 buckets for departments, using a loop to iterate over the `departments` array, which improved resource tracking. I also reinforced the use of environment variables and command-line arguments for dynamic configuration, though the script’s current implementation focuses on fixed values with potential for expansion. Additionally, I mastered error handling with `$?` to check command success, ensuring robust script execution. This project highlighted the power of combining shell scripting with AWS CLI for scalable cloud automation.

## Tools Used
- **Ubuntu Terminal (WSL)**: For script execution and testing.
- **VS Code**: For editing `aws_resources.sh` and `README.md`.
- **Git Bash**: For version control and GitHub push.
- **AWS CLI**: For resource provisioning.

## Project Deliverables
- **Script**: `aws_resources.sh` automates EC2 and S3 creation.
- **Documentation**: This `README.md` includes the learning summary.
- **Script Link**: [GitHub Repository](https://github.com/westgrin/Shell_AWS_Mini_Project)

## Conclusion
This project successfully demonstrated the use of functions and arrays in shell scripting to automate AWS resource provisioning, laying a strong foundation for future cloud automation tasks.