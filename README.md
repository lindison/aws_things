# AWS things for my repo

## Things

### Good Links
Links:
- https://aws.amazon.com/architecture/ 
- https://aws.amazon.com/ec2/

### AWS Services vs EC2 Built Machines
- 

### AWS Instance Types
- http://www.ec2instances.info/

### EC2 Disk Types
- Ephemerial Disks (free disks that come with an EC2 instance)
    - local disk to EC2, performance is quicker
    - static size
    - lifetime tied to instance
    - free w/ EC2 instance
    - user must provision

- EBS (Elastic Block Store) NAS storage for EC2 instances
    - remote rack
    - lifetime is not tied to instance
    - user must provision

### ECS Security Groups
- CIDR Blocks 
    - /16
- Specify Source as a Security Group 

### EC2 User Data
- curl http://169.254.169.254/latest/meta-data 

