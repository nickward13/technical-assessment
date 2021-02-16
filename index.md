# Technical Assessment Questions
This is a living document of key questions to ask when performing a technical assessment.

A technical assessment can be run in a 90 minute session with the partner to get an overview of their application and the key architectural and technical concepts there-in.

The following questions can be used to drive the discussion and ensure a good overview of the system is attained.

## Architecture
- Please provide an architecture diagram
- Is the application an N-tier architecture? Monolith? Microservices?
- What type of tech is used for the app - serverless, web, containers?  Windows or linux?
- Does the app have an API? Is it externally accessible? How is it managed and secured?
- What client apps exist for the app - mobile, web, desktop? What operating systems are supported?

## Code
- What language and/or frameworks is the app built in?
- What repository tech is used and how is code managed?
- Number of devs/ops people?
- Is infrastructure managed as code?  If yes, in what language?

# Data
- What database(s) are used in the solution?
- Is a single monolithic database used, or polyglot persistence model?
- What analytics environment is there - data warehouse, data lake, AI etc.?
- What archiving strategy is used to age out older data?

# Deployment
- Hows is the app deployed - is it per-customer, or multi-tenant?
- How many customers use the app?  What percentage of those customers are on Azure?
- Is the app deployed in the customer's or the ISV's own subscription?
- Are CI/CD processes implemented?  What tooling is used?

# Work processes
- What methodology is used - agile? Waterfall?
- How is the team structured?
- How is the backlog managed?

# Identity
- How is identity managed?  Is an external service used, or built in-house?
- Are any of AAD, AAD B2C or AAD B2B used in the solution?
- Is the app published in the AAD App Gallery?

# Security
- How is security managed in the application?
- Does the application use virtual networks? NSG's?
- Are firewalls / App Gateways / WAFs / network appliances used?
- Is Azure Security Center used?  What is the Azure Secure Score?
- Is a SIEM used, such as Azure Sentinel?

# Availability
- How is high availability managed?
- How is the system backed up?
- Is there a DR environment? How is it managed? Is it in a remote region?

# Scalability
- Does the application use queues to manage load?
- How is the application tier scaled?  Is Event Grid, Service Bus or Event Hub used?
- What are the bottlenecks in the application?
- How is the database tier scaled?
- Are any auto-scaling services used?

# Governance
- What cost management processes / tools are used?
- What management groups / policies / blueprints / controls are in place?
- What monitoring is in place?  Is Azure Monitor, Application Insights and/or Log Analytics used?
