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
Both ephemerial and EBS can be used as a boot drive. Both POSIX compliant. 
- Ephemerial Disks (free disks that come with an EC2 instance)
    - local disk to EC2, performance is quicker
    - cannot be stoppped or started
    - static size
    - cannot be shared
    - lifetime tied to instance
    - free w/ EC2 instance
    - user must provision
    - still volatile 

- EBS (Elastic Block Store) NAS storage for EC2 instances
    - remote rack
    - can be stopped and started
    - lifetime is not tied to instance
    - user must provision
    - can be snapshotted
    - size 1GB to 1TB 

### ECS Security Groups
- CIDR Blocks 
    - /16
- Specify Source as a Security Group 

### EC2 User Data
- curl http://169.254.169.254/latest/meta-data 

