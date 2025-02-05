from azure.identity import DefaultAzureCredential
from azure.mgmt.resource import ResourceManagementClient

# Authenticate using DefaultAzureCredential
credential = DefaultAzureCredential()

# Initialize the Resource Management client
subscription_id = 'your-subscription-id'
resource_client = ResourceManagementClient(credential, subscription_id)

# List resource groups
for rg in resource_client.resource_groups.list():
    print(rg.name)
