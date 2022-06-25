# PowerShell bindings for Carbon Black REST API

_**Notice**:_ 
To learn more about the REST APIs, visit the Carbon Black Developer Network Website at https://developer.carbonblack.com.

## Requirements
1. Carbon Black Cloud Environment
2. Windows PowerShell
3. Active Directory Module for Windows PowerShell

### Security Implications
The PowerShell REST cmdlet (Invoke-RestMethod) sends HTTP or HTTPS requests to a RESTful web service.

### API Token
In order to perform any queries via the API, you will need to get the API token for your CB user. See the documentation
on the Developer Network website on how to acquire the API token for
[CB EDR Cloud](https://developer.carbonblack.com/reference/carbon-black-cloud/platform-apis/authentication/).

The possible options for each credential profile are:

* **uri**: The base URL of the Carbon Black server. This should include the protocol (https) and the hostname.
* **token**: The API token for the user ID. More than one credential profile can be specified for a given server, with
  different tokens for each.
* **orgID**: The organization key. This is required to access the Carbon Black Cloud, and can be found in the console. The format is ``123ABC45``.

## Support

1. View all API and integration offerings on the [Developer Network](https://developer.carbonblack.com/) along with reference documentation, video tutorials, and how-to guides.
2. Use the [Developer Community Forum](https://community.carbonblack.com/t5/Developer-Relations/bd-p/developer-relations) to discuss issues and get answers from other API developers in the Carbon Black Community.
3. Report bugs and change requests to [Carbon Black Support](https://www.vmware.com/support/services.html).
