helps demonstrate how security groups can be attached to ec2 instances and how security groups on two different ec2 instances can allow each other(instances) to connect via SSH.

this demo contains a set(2 items) of 1 security group - 1 ec2 instance combination, where each security group allows the other security group via SSH and there is not need to mention the CIDR for allowing ec2 to connect to each other.
