# istiokeycloak
microservice security
### Istio and Microservices - Security with Keycloak

```
graph TD
A[Istio] -->|request valid token| B(Microservice1) 
A --> C(Keycloak) 
C -->|login to access token| A
C -->|validate access token by Istio| A
```

