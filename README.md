# Auto-m365-user-add
# Automatic User Procurement and Licensing Script
This script automates new user provisioning and license assignment using the Microsoft Graph API.

# Requirements
Python 3.6 or higher

# Microsoft Graph Beta SDK

Microsoft Authentication Library (MSAL) for Python

An Azure Active Directory (Azure AD) application with permissions to access the Microsoft Graph API

# Installation
Install the necessary libraries:

pip install msgraph-beta msal

Create a configuration file (for example config.py) and fill it with your Azure AD application ID, tenant ID and secret key:

CLIENT_ID = 'YOUR_APPLICATION_ID'
CLIENT_SECRET = 'YOUR_APPLICATION_SECRET'
TENANT_ID = 'YOUR_TENANT_ID'
Use code with caution.
Python
Usage
Run the script
Customization
The script can be customized to suit your specific needs. For example, you can modify the script to assign different licenses to users or send different welcome emails to users.

Contribution
Contributions are welcomed! Please feel free to create an issue or submit a pull request to report issues or submit pull requests.

License
This script is licensed under the MIT License.
