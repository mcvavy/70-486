
# __Developing ASP.NET MVC Web Applications__

This list contains links to resources for the 70-486 Developing ASP.NET MVC Web Applications Certification Exam.

## Design the application architecture (15-20%)
- ### Plan the application layers
	- Planning data access
	- Planning for separation of concern (SoC)
	- Using models, views, and controllers appropriately
	- Choosing between client-side and server-side processing
	- Designing for scalability
	
	
- ### Design a distributed application
	- Integrating web services
	- Designing a hybrid application
	- Planning for session management in a distributed environment
	- Planning web farms
	
	
- ### Design and implement the Windows Azure role life cycle
	- Identify and implement Start
	- Run and Stop events; identify startup tasks (IIS configuration [app pool] registry configuration, third-party tools)
	
- ### Configure state management
	- Choose a state management mechanism (in-process and out of process state management, ViewState)
	- Plan for scalability
	- Use cookies or local storage to maintain state
	- Apply configuration settings in web.config file
	- Implement sessionless state (for example, QueryString)

- ### Design a caching strategy
	- Implement page output caching (performance oriented)
	- Implement data caching
	- Implement HTTP caching
	- Implement Azure caching
	
- ### Design and implement a WebSocket strategy
	- Read and write string and binary data asynchronously (long-running data transfers),
	- Choose a connection loss strategy
	- Decide a strategy for when to use WebSockets
	- Implement SignalR
	
- ### Design HTTP modules and handlers
	- Implement synchronous and asynchronous modules and handlers
	- Choose between modules and handlers in IIS
	
## Design and implement security (20-25%)
- ### Configure authentication
	- Authenticate users; enforce authentication settings; choose between Windows, Forms and custom authentication; 
	- Manage usersession by using cookies; configure membership providers; 
	- Create custom membership providers;
	- Configure ASP.NET Identity

- ### Configure and apply authorisation
	- Create roles
	- Authorise roles by using configuration
	- Authorise roles programmatically
	- Create custom role providers
	- Implement WCF service authorisation

- ### Design and implement claims-based authentication across federated identity stores
	- Implement federated authentication by using Azure Access Control Service
	- Create a custom security token by using Windows Identity Foundation
	- Handle token formats (for example, oAuth, OpenID, Microsoft Account, Google, Twitter and Facebook) for SAML and SWT tokens

- ### Manage data integrity
	- Apply encryption to application data
	- Apply encryption to the configuration sections of an application
	- Sign application data to prevent tampering

- ### Implement a secure site with ASP.NET
	- Secure communication by applying SSL certificates
	- Salt and hash passwords for storage
	- Use HTML encoding to prevent cross-site scripting attacks (ANTI-XSS Library)
	- Implement deferred validation and handle unvalidated requests, for example, form, querystring and URL; prevent SQL injection attacks by parameterising queries; prevent cross-site request forgeries (XSRF)
