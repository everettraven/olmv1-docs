# Operator Lifecycle Manager (OLM)
Operator Lifecycle Manager (OLM) is a Kubernetes extension that makes installing, running, and updating functional extensions to the cluster easy, safe, and reproducible for cluster administrators and PaaS administrators, throughout the lifecycle of the underlying cluster.

## Tenets

### Do not fight Kubernetes
elaboration needed
### Secure by Default
elaboration needed
### Simple, Predictable Semantics for Install, Upgrade, and Delete
elaboration needed
### Handle Common Controller Patterns Without Limiting Installable Content
elaboration needed

### Constraint Checking Without Automated On-Cluster Management
elaboration needed

### Client Tooling is for Users
elaboration needed

## Architecture
OLM is currently distributed across two separate projects:
- catalogd: A controller for unpacking and serving contents of a catalog of Kubernetes extensions
- operator-controller: A controller for managing the installation of a Kubernetes extension

**Architecture Diagram Here**
