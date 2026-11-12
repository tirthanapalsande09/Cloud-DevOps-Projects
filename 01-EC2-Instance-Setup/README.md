
# AWS EC2 Instance Creation and Configuration (Linux & Windows)

## Project Overview
This project demonstrates how to launch and configure Linux and Windows virtual machines using Amazon EC2 (Elastic Compute Cloud) through the AWS Management Console.

## Objectives
- Understand AWS EC2 and its functionality.
- Launch a Linux EC2 instance.
- Launch a Windows EC2 instance.
- Configure key pairs and security groups.
- Connect to Linux using SSH.
- Connect to Windows using Remote Desktop Protocol (RDP).

## Technologies Used
- Amazon Web Services (AWS)
- Amazon EC2
- Linux (Ubuntu/Amazon Linux)
- Windows Server
- SSH
- Remote Desktop Protocol (RDP)
- AWS Management Console

## Implementation Steps

### 1. Launch Linux EC2 Instance
1. Open AWS Management Console.
2. Navigate to EC2.
3. Select Launch Instance.
4. Choose a Linux AMI.
5. Select an instance type.
6. Configure key pair and security group.
7. Launch the instance.

### 2. Connect to Linux Instance
1. Select the running EC2 instance.
2. Click Connect.
3. Choose EC2 Instance Connect or SSH client.
4. Establish a connection.

### 3. Launch Windows EC2 Instance
1. Navigate to EC2 Dashboard.
2. Select Launch Instance.
3. Choose a Windows Server AMI.
4. Select an instance type.
5. Create or select a key pair.
6. Configure security group.
7. Launch the instance.

### 4. Connect to Windows Instance
1. Select the running Windows instance.
2. Choose Connect.
3. Open the RDP client option.
4. Retrieve the administrator password using the key pair.
5. Connect using Remote Desktop.

## Security Configuration
- Allow SSH (Port 22) only from your trusted IP.
- Allow RDP (Port 3389) only from your trusted IP.
- Use secure key pairs.
- Avoid exposing administrative access to the entire internet.
- Stop instances when they are not required.

## Expected Outcome
Successfully launch and access Linux and Windows virtual machines on AWS EC2.

## Skills Gained
- AWS EC2 instance management
- Linux and Windows server deployment
- SSH and RDP connectivity
- AWS security group configuration
- Cloud infrastructure fundamentals

## Author
Tirthana Palsande

## License
This project is intended for educational and learning purposes.
