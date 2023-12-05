# Deployment View #
## CAP Theorem ##
We are considering AP because we aim for high availability and partition tolerance, because we are using an app.
Mobile apps are often vulnerable to connection issues, so we are considering partition, so our system keeps working.

Same goes for availability. Data can be retrieved even when partial failures are accruing.  

We are also considering a Saga Pattern, so payments can be done with no issues. It helps us  ensuring data consistency in microservices architectures where each service has its own database. 

## Deployment diagram ##
![grafik](https://github.com/Csisko3/SWARC-CarCompass/assets/131276050/b2654843-8f88-4473-95b0-c56b0cb6f548)
