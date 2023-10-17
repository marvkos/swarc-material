# Solutions and Risks # 

### Solution Strategy ###
 Goal/Requirements       | Architectural Approach      |
| ------------- |:-------------------:|
|Third-party-payment system connection should constant| SOA (Using existing services to minimizes workload)|
|Continues deployment | Microservices (continues deployment, bug fixing, fast response…)|
|Scalability| Microservices (to handle increased usage without effective performance)|


 ## Architecture Decisions ##
 Problem| Considered Alternatives| Decision|
|:--------:|------------| ------------|
|Services doesn’t work (payment)| Make own payment service, use more services (intern.) | We decided to make our own payment service.|
|OS compatibility problems| Use compatibility patches, rewrite code for compatibility| We are considering using compatibility patches.|
|Cost management |  Cloud services costs need to be monitored and managed | We are implementing cost monitoring measures.|


## Risks and Technical Debt ##
Risk/Technical Debt| Description|
| ------------- |:-------------------:|
|Complexity| Managing the many microservices at once |
|Delays (SOA)| Response time can be increased going threw more services |
|Outdated technology | International companys have maybe services that are older and can lead to higher maintance costs, security issues, finding developers…|


