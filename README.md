# Community Model Context Protocol Registry (Experimental)
> [!NOTE]
> Powered by [Azure API Center](https://learn.microsoft.com/en-us/azure/api-center/register-discover-mcp-server) <img src="https://apidev.gallerycdn.vsassets.io/extensions/apidev/azure-api-center/1.1.2025051305/1747194036358/Microsoft.VisualStudio.Services.Icons.Default" width="30" height="30">

## Try - https://demo.registry.azure-mcp.net/v0/servers

- Implements the [Model Context Protocol Registry](https://github.com/modelcontextprotocol/registry/blob/main/api/README.md) specification
- Supports List, Get and Publish operations. 
    - For publishing please follow [instructions](https://github.com/modelcontextprotocol/registry/blob/main/tools/publisher/README.md)

### Azure API Center - Enterpise Registry
Enterprises can use [Azure API Center](https://github.com/azure/api-center) a key feature of [Azure API Management](https://learn.microsoft.com/en-us/azure/api-management/api-management-key-concepts) platform to maintain an inventory (or registry) of remote model context protocol (MCP) servers, govern and help stakeholders discover and consume them using the API Center portal and developer tools. 

The rich [metadata](https://learn.microsoft.com/en-us/azure/api-center/metadata) capabilites enables enterprises to model and augument information in ways it fits their organizational inventory, governance and compliance requirments. Example, In the above implementation, local MCP servers were modeled using the [custom metadata](https://learn.microsoft.com/en-us/azure/api-center/metadata#custom-metadata)  functionality.

**Learn more** -
- Repo: https://github.com/azure/api-center

- Documentation : https://aka.ms/apicenter/docs/mcp

- Video: https://youtu.be/8bDDPMz1gjQ

Please contact the Azure API Center team directly at apicenter@microsoft.com for any questions and queries around hosting and governing MCP servers for your enterprise.   