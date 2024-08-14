# Write-up Template
 
### Analyze, choose, and justify the appropriate resource option for deploying the app.
 
For VM
Cost: Higher initial costs due to need to allocate resource upfront
Scalability: Scaling VMs is possible with both vertical and horizontal
Availability: Need to configure and manage availability sets to ensure hight availability
Workflow: Provide more control over the environment
 
For App Service:
Cost: Lower initial costs
Scalability: While vertical scaling is limited, it is support horizontal scaling
Availability: It provides auto-scaling and built-in load balancing feature
Workflow: Provide a simple deployment process, easy intergration with GitHub
 
I choose App Service to deploy my application because:
- It is cost effective
- The application is scale automatically
- No need to worry about network, setup invironment or infrastructure.
- Using SQL database and Storage Account for data and images storage, so I dont need to use VMs
- My applicatoin workflow benefit from intergration with CI/CD pipelines
 
### Assess app changes that would change your decision.
 
- If the application require more complex setting and use technologies that App Service does not support, then I will change to Virtual Machines.
- Reason: VM will provide full control, allow me to freely customize the setting and environment to satisfy the requirement
 
