## Udagram High-Available Application in AWS automated by Cloudformation service

This is an Infrastructre as a Code using Cloudformation service in AWS, to provision an infrastructure for Udagram app in AWS

### Scripts

Shell scripts are available in ```scripts``` folder to create, describe and update the stack


## Architecture Diagram
![Alt design](design/infra.png)

## Screenshot from Cloudformation dashboard (ALB custom generated DNS URL)
![Alt dashboard](design/cloudformation-output.png)

## Screenshot of the server response to the URL
![Alt response](design/server-response.png)

### Generated URL of the load balancer is: http://WebLoadBalancer-1661604713.us-west-2.elb.amazonaws.com
