# Azure Networking and Storage Project

This project contains ARM templates to deploy a secure networking and storage setup in Microsoft Azure.

## Components

### 🔹 Virtual Network (VNet)
- Two subnets: Web and Database
- NSG associated with Web subnet
- Service endpoint enabled for Microsoft.Storage

### 🔹 Storage Account
- Private endpoint configured to Database subnet
- Public access disabled
- Encryption enabled using Microsoft-managed keys

## Structure

azure-networking-storage-project/
├── vnet-template/
│ ├── template.json
│ └── parameters.json
├── storage-template/
│ ├── template.json
│ └── parameters.json


## Deployment

Templates were exported from the Azure Portal and can be redeployed via Template Specs or Azure CLI.

---

## Author

Johnny Hanna — Azure Certified, Infrastructure & Data Admin

