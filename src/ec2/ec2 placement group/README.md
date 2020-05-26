helps demonstrate how placement groups can be used to logically group ec2 instances in a particular availability zone.

this demo will attach 2 instances to partition placement group and 1 instance to spread placement group. cluster placement group was not preferred because of the predicted cost of using a high end instance type relative to t2.micro as t2.micro based instance is not allowed to be placed in cluster placement group.
