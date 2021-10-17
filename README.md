# Azure Cost Management Runbook

A Python script (Runbook) for getting the daily cost of azure resources in subscription level.

## Prerequiste

- [Python](https://www.python.org/downloads/) 3.7+
- [Azure](https://portal.azure.com/#home) Account
- Any code editor. (Preferable: [VS Code](https://code.visualstudio.com/download))

## Python packages

| Package | Uses |
| ------ | ------ |
| [Adal](https://pypi.org/project/adal/) or [MSAL](https://pypi.org/project/msal/) | The Microsoft Authentication Library for Python enables applications to integrate with the Microsoft identity platform. [PlDb] |
| [Requests](https://pypi.org/project/requests/) | Requests is a simple, yet elegant, HTTP library. [PlGh] |
| [AutomationAssets](https://pypi.org/project/azure-mgmt-automation/) | This is the Microsoft Azure Automation Client Library. [PlGd] |
| [Pandas](https://pypi.org/project/pandas/) | Pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or      "labeled" data both easy and intuitive. [PlOd] |
| [Pretty_html_table](https://pypi.org/project/pretty-html-table/) | pretty_html_table exists to convert a pandas DataFrame into a pretty html table for use in email. The intended target audience is anyone who needs to send reports via email and would like to make their tables look more attractive. [PlMe] |
| SMTPLib | Smtp Lib is a client library which will help you in sending the mail. [PlGa] |

## Insallation

- Install all the above mentioned packages through `pip install <package-name>`.
- Login to [Azure](https://portal.azure.com/#home) account.
- Search `Cost Management + Billing` and navigate to `Cost Management` > `Cost analysis` and, then set filter based on your requirement.

## Run Script

- Run the `azureCostMgmt.py` to get the daily usage data. 

# Blog

You can checkout my [blog](https://medium.com/@cprasad1512) for more information about this.