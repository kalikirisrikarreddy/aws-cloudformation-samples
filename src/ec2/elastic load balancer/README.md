helps demonstrate how an application load balancer can route requests to
instances behind it.

this demo contains an internet facing load balancer sending requests to
3 instances behind it. we used an internet facing load balancer to test from
outside aws. the three instances can only be contacted by the load balancer,
and load balancer is available for the api users. 
