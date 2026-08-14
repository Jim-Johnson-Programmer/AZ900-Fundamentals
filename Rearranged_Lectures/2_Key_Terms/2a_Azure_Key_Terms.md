# Benefits of Cloud Computing Terms

- **_High Availability_**: Cloud environments are based on virtual environments that are designed to be highly available. Adding VM's, components, and services is done with a credit card in minutes, not weeks of setup.\*\*
- **_Fault Tolerance:_** If a component fails, the system will automatically recover and continue to operate.\*\*
- **_Disaster Recovery_**: Since cloud environment are virtual, they can be replicated to other regions and data centers. This allows for disaster recovery in the event of a catastrophic failure.
- **_Scalability_**: Be careful not to confuse scalability with elasticity. Scalability is the ability to increase resources where the INCREASE REMAINS IN PLACE AFTER THE ADJUSTMENT.
  - You purchase extra resources following a surge in traffic, and the resources remain in place after the surge is over.
  - You increase your subscription to a higher tier of service to handle a surge in traffic, and the subscription remains at the higher tier after the surge is over.
- **_Elasticity:_** is the SYSTEM CREATING DYNAMIC RESOURCES TO HANDLE A SURGE, THEN RELEASING THE RESOURCES AFTER THE SURGE.
  - Example is Kubernetes scaling up pods to handle a surge in traffic, then scaling down after the surge is over.
  - Example is a full queue of messages in a Service Bus topic that is processed by a function app. The function app will scale up to handle the surge, then scale down after the surge is over.
- **_Agility_**: In dev world, speed at which you can respond to bugs and get the fix through the SDLC. In server world, speed at which you can make your server and network scalability happen to respond to need.
- **_Reliabilty:_**
  - Cloud providers have multiple data centers in multiple regions. If one data center goes down, the other data centers can take over the load.
  - Cloud providers have multiple availability zones in each region. If one availability zone goes down, the other availability zones can take over the load.

# Terms of Cloud Computing

- CapEx (Capital Expenditure): The cost of purchasing physical hardware and software. This is a one-time cost that is incurred upfront.
  - Example: Purchasing a server, storage device, or networking equipment.
- OpEx (Operational Expenditure): The cost of using cloud services. This is a recurring cost that is incurred on a monthly or annual basis.
  - Example: Paying for a subscription to a cloud service, such as Azure.
  - Example: Labor costs for managing and maintaining cloud services.
