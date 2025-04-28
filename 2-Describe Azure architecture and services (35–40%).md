# ☁️ **AZ-900: Describe Azure Architecture and Services (35–40%)**

---

## 🏛️ **Describe the Core Architectural Components of Azure**

- 🌍 [**Azure Regions**](https://azure.microsoft.com/en-ca/explore/global-infrastructure/geographies/)
- ♻️ [**Region Pairs**](https://learn.microsoft.com/en-us/azure/reliability/cross-region-replication-azure)
- 🛡️ [**Sovereign Regions**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/regions#sovereign-regions)
- 🏢 [**Availability Zones**](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview)
- 🏗️ [**Azure Datacenters**](https://azure.microsoft.com/en-us/explore/global-infrastructure/)
- 🔧 [**Azure Resources**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-resource)
- 📂 [**Resource Groups**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-resource-group)
- 📜 [**Subscriptions**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-subscription)
- 🏢 [**Management Groups**](https://learn.microsoft.com/en-us/azure/governance/management-groups/overview)
- 🏛️ [**Hierarchy of Resources**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources) (Resource Groups ➡️ Subscriptions ➡️ Management Groups)

---

## 🚀 **Describe Azure Compute and Networking Services**

- 🖥️ **Compare Compute Types**:
  - 📦 [**Containers**](https://azure.microsoft.com/en-ca/resources/cloud-computing-dictionary/what-is-a-container/)
  - 🖥️ [**Virtual Machines**](https://azure.microsoft.com/en-ca/resources/cloud-computing-dictionary/what-is-a-virtual-machine/)
  - ⚡ [**Azure Functions**](https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview)

- 🖥️ **Virtual Machine Options**:
  - [**Azure VMs**](https://learn.microsoft.com/en-ca/azure/virtual-machines/overview)
  - [**VM Scale Sets**](https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
  - [**Availability Sets**](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview)
  - [**Azure Virtual Desktop**](https://learn.microsoft.com/en-us/azure/virtual-desktop/overview)

- 🔨 [**Resources Needed for VMs**](https://learn.microsoft.com/en-us/azure/virtual-machines/overview#what-do-i-need-to-think-about-before-creating-a-virtual-machine)

- 🏗️ **Application Hosting Options**:
  - 🌐 [**Web Apps**](https://learn.microsoft.com/en-us/azure/app-service/overview)
  - 📦 Containers
  - 🖥️ [**Virtual Machines**](https://learn.microsoft.com/en-ca/azure/virtual-machines/overview)

- 🌐 **Virtual Networking**:
  - [**Azure VNets**](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
  - Azure Subnets
  - 🔗 [**Peering**](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview)
  - 🧭 [**Azure DNS**](https://learn.microsoft.com/en-us/azure/dns/dns-overview)
  - 🔒 [**VPN Gateway**](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
  - ⚡ [**ExpressRoute**](https://learn.microsoft.com/en-us/azure/expressroute/expressroute-introduction)

- 🌐 Define **Public Endpoints**  
- 🔒 [**Private Endpoints**](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-overview)

---

## 💾 **Describe Azure Storage Services**

- 📦 [**Compare Storage Services**](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)
- 📊 [**Storage Tiers**](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview)
- ♻️ [**Redundancy Options**](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy)
- 🗄️ [**Storage Accounts and Types**](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview)

- 🚚 **Moving Files**:
  - 📤 [**AzCopy**](https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10)
  - 🛠️ [**Azure Storage Explorer**](https://azure.microsoft.com/en-ca/products/storage/storage-explorer)
  - 🔗 [**Azure File Sync**](https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-introduction)

- 🚀 **Migration Options**:
  - 🛠️ [**Azure Migrate**](https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview)
  - 📦 [**Azure Data Box**](https://learn.microsoft.com/en-us/azure/databox/data-box-overview)

---

## 🔒 **Describe Azure Identity, Access, and Security**

- 🗃️ **Directory Services**:
  - 🔑 [**Microsoft Entra ID**](https://learn.microsoft.com/en-us/entra/fundamentals/whatis)
  - 🏢 [**Microsoft Entra Domain Services**](https://learn.microsoft.com/en-us/entra/identity/domain-services/overview)

- 🛡️ **Authentication Methods**:
  - 🔑 [**Single Sign-On (SSO)**](https://learn.microsoft.com/en-us/entra/identity/enterprise-apps/what-is-single-sign-on)
  - 📲 [**Multi-Factor Authentication (MFA)**](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks)
  - 🛡️ [**Passwordless Authentication**](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-passwordless)

- 🌍 [**External Identities**](https://learn.microsoft.com/en-us/entra/external-id/external-identities-overview):
  - 🤝 [**B2B (Business-to-Business)**](https://learn.microsoft.com/en-us/entra/external-id/what-is-b2b)
  - 🛒 [**B2C (Business-to-Consumer)**](https://learn.microsoft.com/en-us/azure/active-directory-b2c/overview)

- 🎯 [**Conditional Access**](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)
- 🛠️ [**Azure Role-Based Access Control (RBAC)**](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview)
- 🔐 [**Zero Trust Concept**](https://www.microsoft.com/en-ca/security/business/zero-trust/)
- 🛡️ [**Defense-in-Depth Model**](https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/) | [📄 PDF Version](https://info.microsoft.com/rs/157-GQE-382/images/Defense_In_Depth_Enterprise%20Mobility_and_Security_61517.pdf)
- 🛡️ [**Microsoft Defender for Cloud**](https://learn.microsoft.com/en-ca/azure/defender-for-cloud/defender-for-cloud-introduction)

---
