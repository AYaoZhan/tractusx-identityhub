# Developer Documentation Hub

This directory contains comprehensive documentation for developers working with the Tractus-X IdentityHub and IssuerService.

## Required Knowledge

To effectively work with this project, familiarity with the following technologies is recommended:

- **Kubernetes**: Container orchestration platform for deploying and managing the applications
- **Minikube**: Local Kubernetes environment for development and testing
- **Helm**: Package manager for Kubernetes, used for deploying the charts
- **PostgreSQL**: Relational database used for persistent storage
- **HashiCorp Vault**: Secrets management system for secure credential storage

## Best Practices

- Use the official Helm charts for all deployments
- Follow the [Installation Guide](../INSTALL.md) for local development setup
- Test API endpoints using the provided Postman or Bruno collections

> [!NOTE]
> When testing, it is recommended to enable ingress to avoid working with port-forwarding. Refer to the respective chart documentation for ingress configuration options, including hostname, TLS settings, and annotations.

## Documentation Resources

### [API Documentation](./api/README.md)

Complete API reference and testing resources, including:

- **OpenAPI Specification**: Full API documentation with endpoints, schemas, and authentication requirements
- **Postman Collection**: Ready-to-use Postman collection for issuance flow testing
- **Bruno Collection**: Lightweight, Git-friendly API collection for Bruno
- **Testing Guide**: Instructions for setting up and running API tests

### [Migration Guide](./admin/migration-guide.md)

Administrator guide for migrating between chart versions, including:

- Chart version migration instructions
- Bitnami dependency updates and image repository changes
- PostgreSQL version compatibility notes

