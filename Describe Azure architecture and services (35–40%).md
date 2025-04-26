# ☁️ **AZ-900: Describe Azure Architecture and Services (35–40%)**

---

<details>
<summary>🏛️ <strong>Describe the Core Architectural Components of Azure</strong></summary>

- 🌍 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Regions**](https://azure.microsoft.com/en-ca/explore/global-infrastructure/geographies/)
- ♻️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Region Pairs**](https://learn.microsoft.com/en-us/azure/reliability/cross-region-replication-azure)
- 🛡️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Sovereign Regions**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/regions#sovereign-regions)
- 🏢 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Availability Zones**](https://learn.microsoft.com/en-us/azure/reliability/availability-zones-overview)
- 🏗️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Datacenters**](https://azure.microsoft.com/en-us/explore/global-infrastructure/)
- 🔧 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Resources**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-resource)
- 📂 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Resource Groups**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-resource-group)
- 📜 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Subscriptions**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works#what-is-an-azure-subscription)
- 🏢 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Management Groups**](https://learn.microsoft.com/en-us/azure/governance/management-groups/overview)
- 🏛️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Hierarchy of Resources**](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources) (Resource Groups ➡️ Subscriptions ➡️ Management Groups)

</details>

---

<details>
<summary>🚀 <strong>Describe Azure Compute and Networking Services</strong></summary>

- 🖥️ **Compare Compute Types**:
  - 📦 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Containers**](https://azure.microsoft.com/en-ca/resources/cloud-computing-dictionary/what-is-a-container/)
  - 🖥️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Virtual Machines**](https://azure.microsoft.com/en-ca/resources/cloud-computing-dictionary/what-is-a-virtual-machine/)
  - ⚡ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Functions**](https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview)

- 🖥️ **Virtual Machine Options**:
  - <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure VMs**](https://learn.microsoft.com/en-ca/azure/virtual-machines/overview)
  - <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**VM Scale Sets**](https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
  - <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Availability Sets**](https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview)
  - <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Virtual Desktop**](https://learn.microsoft.com/en-us/azure/virtual-desktop/overview)

- 🔨 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Resources Needed for VMs**](https://learn.microsoft.com/en-us/azure/virtual-machines/overview#what-do-i-need-to-think-about-before-creating-a-virtual-machine)

- 🏗️ **Application Hosting Options**:
  - 🌐 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Web Apps**](https://learn.microsoft.com/en-us/azure/app-service/overview)
  - 📦 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> Containers
  - 🖥️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Virtual Machines**](https://learn.microsoft.com/en-ca/azure/virtual-machines/overview)

- 🌐 **Virtual Networking**:
  - <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure VNets**](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
  - <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> Azure Subnets
  - 🔗 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Peering**](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview)
  - 🧭 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure DNS**](https://learn.microsoft.com/en-us/azure/dns/dns-overview)
  - 🔒 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**VPN Gateway**](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
  - ⚡ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**ExpressRoute**](https://learn.microsoft.com/en-us/azure/expressroute/expressroute-introduction)

- 🌐 Define **Public Endpoints**
- 🔒 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Private Endpoints**](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-overview)

</details>

---

<details>
<summary>💾 <strong>Describe Azure Storage Services</strong></summary>

- 📦 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Compare Storage Services**](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)
- 📊 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Storage Tiers**](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview)
- ♻️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Redundancy Options**](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy)
- 🗄️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Storage Accounts and Types**](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview)

- 🚚 **Moving Files**:
  - 📤 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**AzCopy**](https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10)
  - 🛠️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Storage Explorer**](https://azure.microsoft.com/en-ca/products/storage/storage-explorer)
  - 🔗 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure File Sync**](https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-introduction)

- 🚀 **Migration Options**:
  - 🛠️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Migrate**](https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview)
  - 📦 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Data Box**](https://learn.microsoft.com/en-us/azure/databox/data-box-overview)

</details>

---

<details>
<summary>🔒 <strong>Describe Azure Identity, Access, and Security</strong></summary>

- 🗃️ **Directory Services**:
  - 🔑 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Microsoft Entra ID**](https://learn.microsoft.com/en-us/entra/fundamentals/whatis)
  - 🏢 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Microsoft Entra Domain Services**](https://learn.microsoft.com/en-us/entra/identity/domain-services/overview)

- 🛡️ **Authentication Methods**:
  - 🔑 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Single Sign-On (SSO)**](https://learn.microsoft.com/en-us/entra/identity/enterprise-apps/what-is-single-sign-on)
  - 📲 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Multi-Factor Authentication (MFA)**](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks)
  - 🛡️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Passwordless Authentication**](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-passwordless)

- 🌍 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**External Identities**](https://learn.microsoft.com/en-us/entra/external-id/external-identities-overview):
  - 🤝 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**B2B (Business-to-Business)**](https://learn.microsoft.com/en-us/entra/external-id/what-is-b2b)
  - 🛒 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**B2C (Business-to-Consumer)**](https://learn.microsoft.com/en-us/azure/active-directory-b2c/overview)

- 🎯 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Conditional Access**](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview)
- 🛠️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Azure Role-Based Access Control (RBAC)**](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview)
- 🔐 <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Zero Trust Concept**](https://www.microsoft.com/en-ca/security/business/zero-trust/)
- 🛡️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Defense-in-Depth Model**](https://azure.microsoft.com/en-us/blog/microsoft-azures-defense-in-depth-approach-to-cloud-vulnerabilities/) | [📄 PDF Version](https://info.microsoft.com/rs/157-GQE-382/images/Defense_In_Depth_Enterprise%20Mobility_and_Security_61517.pdf)
- 🛡️ <img src="https://azure.microsoft.com/favicon.ico" width="16" height="16" align="absmiddle"> [**Microsoft Defender for Cloud**](https://learn.microsoft.com/en-ca/azure/defender-for-cloud/defender-for-cloud-introduction)

</details>
