## Azure Resources

- Building blocks of Azure infrastructure, such as Virtual Machines, databases, and storage accounts.
- Each resource can be managed individually.

### Resource Groups in Azure

- Logical containers for related Azure resources.
- Organize resources by project, application, or environment.
- Support centralized access management through RBAC.
- Enable collective resource management.

<img src="https://ravichaganti.com/images/armin30/d1-armarch.png" alt="Azure Resource Manager Architecture" width="700">

### Azure Resource Manager (ARM)

- Azure's deployment and management service.
- Uses ARM templates (JSON) for repeatable deployments.
- Manages resource dependencies and deployment order.
- Supports resource organization using tags.
- Provides a consistent layer for creating, updating, and deleting resources.


### Azure Resource Providers

- Enable the creation and management of specific Azure resource types.
- Each Azure resource type has an associated resource provider.
- Azure Resource Manager (ARM) provides a unified management layer for Azure resources.

#### Ways to Manage Azure Resources

- Azure PowerShell
- Azure CLI
- Azure SDKs (Python, Go, etc.)
- Azure REST API
