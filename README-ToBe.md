# To-Be state architecture

## Architecture

<br/>

![To-Be Architecture](./assets/HLSD-ToBe-Draft%20V1.png)

- Introduce Azure API Management (APIM) as API gateway instead of `Kong`
- Implement feature `Development Portal` to provide API documentation for developers
- Implement `Product` to group APIs for each purpose
- Implement `mTLS` for communication between APIM and backend service (AKS)
- Implement IP whitelist for communication between APIM and backend service (AKS)
- Implement `OAuth 2.0` for API security
- Implement `AKS` for backend service runtime
- Implement related kubernetes resources
- Github Action for CICD
- Azure Monitor for monitoring metrics and log and including access log (requeat/response)
- Azure Container Registry
- Azure KeyVault
- Azure MySQL for application (mock)
