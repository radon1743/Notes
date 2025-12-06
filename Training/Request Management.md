#ifs 	#ServiceManagement

Request management is the process to manage the lifecycle of the Service Requests received from customers.

	Request -> Dispatch -> Execution -> Invoicing


Request Initiation 
![[Pasted image 20251202103314.png]]
![[Pasted image 20251202104443.png]]
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

# BDR
in service management refers to "Business Data Requirements." It describes the specific data requirements necessary for managing various aspects of service management, such as handling customer orders, service contracts, and service level agreements (SLAs

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
[[IFS MWO Service]]



- Request type: The kind of request, such as incident, service request, complaint, etc., used to drive routing and behavior.​
    
- Importance: Business importance or customer priority (for example, VIP vs. normal) that helps decide which requests to handle first within the same severity.​
    
- Group: A high-level bucket for grouping requests (for example, IT, Facilities, Maintenance) to organize work and reporting.​
    
- Request category: A more detailed classification under the group/type (for example, “Network issue” or “Plumbing”) so you can analyze and route similar issues together.​
    
- Urgency: How quickly the issue needs attention (time criticality), which together with impact/severity often drives the final priority.​
    
- Problem symptoms: Standard codes or descriptions of what the user is experiencing (for example, “no power,” “leak,” “error message”) to make problem analysis and searching easier.​
    
- Visibility: A flag or value that controls who can see the request (for example, internal only, customer visible) and can also be used for filtering and grouping.​
    
- Severity: How big the impact is on business or safety (for example, critical, major, minor), used to define response targets and escalations.​
    
- Class: A general classification code used to tag and group requests for reporting or rules (for example, by product line, service line, or other internal scheme)


### Pickup task

- The pickup task shows which parts must be collected, from which supplier or warehouse, by when, and who is assigned to do the pickup; once done, the picked parts are received and reserved to the main request task.[](https://docs.ifs.com/ifsclouddocs/25r2/RequestManagement/AboutPickupTask.htm)​
    
- It is automatically created when a request task has material lines with delivery method “Pick Up,” and it can be planned, scheduled, and executed (including via Mobile Work Order) just like other tasks, but its only purpose is to perform the material pickup.[](https://docs.ifs.com/ifsclouddocs/25r2/RequestManagement/AboutPickupTask.htm)​

### Peg Material 
Peg material demand means creating a fixed link between an incoming supply (like a purchase order or shop order) and a specific material demand line on your request/work task.​

- When you peg demand, the system “pre‑reserves” that future supply for that exact demand, so when the parts arrive into inventory they are automatically allocated to that task


## Recurring Service
A recurring service is a service that is performed repeatedly on a defined schedule, instead of just once.​

Service triggers  
- Service triggers define the logic that decides when a recurring service occurs:  
- Calendar-based (every X days/weeks/months/years).  
-  Usage-based (e.g., after X hours, km, cycles).  
- Condition-based (based on readings within or outside defined limits)

 Service scopes
- Service scopes define the actual recurring services that will be executed at those occurrences, including which service, object/model, and cycle pattern they follow.
