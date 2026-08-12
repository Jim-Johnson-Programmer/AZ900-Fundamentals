# xAAS, Serverless, and Availability

Anything-as-a-Service (XaaS) describes the broad cloud model where capabilities are delivered as services rather than as owned infrastructure. Serverless is a cloud execution model where the provider manages most infrastructure concerns and billing often follows actual execution.

## XaaS

- Includes IaaS, PaaS, SaaS, and many specialized managed services.
- Shifts operational work from the customer to the provider.
- Improves speed of adoption and reduces infrastructure management overhead.

1. Infrastructure as a Service (IaaS), you manage virtual machines, storage, and networking while the provider manages the physical hardware. Hardware is abstracted away, but you still manage the operating system and applications.
2. Platform as a Service (PaaS), you manage applications and data while the provider manages the underlying infrastructure, operating system, and runtime. You focus on building and deploying applications without worrying about the underlying servers. This is most of Azure's managed services, such as Azure App Service, Azure SQL Database, and Azure Kubernetes Service.
3. Software as a Service (SaaS), you use the provider's application without managing the underlying infrastructure, operating system, or application code. Examples include Microsoft 365, Dynamics 365, and Salesforce.

## Serverless

- You focus on code or business logic rather than server management.
- Capacity can scale automatically.
- Billing is often based on executions, run time, or events.
- Most commonly is Azure Functions, but other services like Azure Logic Apps and Azure Event Grid also follow serverless principles.

## Availability Benefits

- Managed services often provide built-in resiliency and scaling.
- Serverless platforms can react quickly to changes in demand.
- Operational burden is reduced because patching and host maintenance are largely handled by Azure.

## Exam Focus

- Serverless does not mean no servers exist; it means you do not manage them directly.
- Azure Functions is a key serverless example.
- XaaS represents the broader service delivery mindset in cloud computing.
