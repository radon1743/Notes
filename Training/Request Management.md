#ifs 	#ServiceManagement

Request management is the process to manage the lifecycle of the Service Requests received from customers.

	Request -> Dispatch -> Execution -> Invoicing

## Request Management  Basic Data
Request Category,
Request Class
Request Group
Request importance 
Request Severity 
* Request Type 
Request Visibility 
- Request Urgencies 
- Problems/ Symptoms 
- Priority 


Data needed to handle request efficiently
- Scope
- Problem if need
- Object information
- Service and Contract information
- Classification details
- SLA details etc.


![[Pasted image 20251110105208.png]]
## Price Rule 
- A price rule controls how a customer is charged
- Can have multiple pricing rule lines for different Sales and Groups and cost type
- Connected to service, warranty or contract line
- Scope, Group, Cost type, etc
- Money of the service

## Service Level Agreement (SLA)
- A formal contract between a Service provider and a customer that defines the level of service expected
- Measurable metrics, Uptime, response time
- Responsibilities and exclusions 
- penalties 
- Scope of the service

## Standard Task
- A standard task is predefined execution procedure 
- **Can be defined using Standard Task Library**
- Dependencies can be created between standard task 
- Implementation of the service


## Service Catalog 
Group of services offered to customers
- Description 
- Delivery Method
- Service method
- You can connect Service Organization to Service Catalog

## Service Resources 
	Resource something that can be used in planning and executing the processes in IFS Cloud. 
	e.g. Machine, Machine Group, Person, Person Group, Tool/Eqp, Crew and crew grp

The Service resources are resources that can be planned and allocated on work tasks in Request Management for service.  **Use in Service** indicator on the resource group needs to be set to yes.


## Warehouse Basic Data

![[Pasted image 20251112155811.png]]


## Inventory locations
- Arrival (Arrived at the warehouse)
- Quality Assurance (QA by the team before storing)
- Production Line (Used for manufacturing process)
- Picking (Frequently used parts request work task)
- Shipment (Delivered to customers)
- Floor Stock (Store the parts to be used in manufacturing)


# Request Initiation 

Create Request - Prerequisites
- Customer 
- Service (New Service assistant)
- The Service Org needs to be connected to Services in the service Catalog
- If needed Reported Item Model and Objects
- Model in the Model page 
- The request contract agencies 
- Request Contracts should be defined with a Contract Line with a Price Rule 