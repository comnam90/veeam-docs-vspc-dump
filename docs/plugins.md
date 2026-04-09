---
title: "Plugins and Integration"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/plugins.html"
last_updated: "1/9/2026"
product_version: "9.2.0.33215"
---

# Plugins and Integration


Veeam Service Provider Console offers built-in integration with third party solutions through predefined plugins. Plugins allow you to combine functionality of Veeam Service Provider Console with the functionality of other platforms and consolidate client data from different sources in one place. You can find the list of available integrations on the Veeam Service Provider Console Configuration > Catalog tab.

Veeam Service Provider Console offers the following predefined integrations:

* [Integration with Veeam Cloud Connect](integration_cc.md).

* [Integration with Veeam Backup & Replication](integration_vbr.md).
* [Integration with Veeam Data Cloud Vault](integration_vault.md).
* [Integration with Veeam Backup for Microsoft 365](integration_vbo.md).
* [Integration with Veeam Backup for Public Clouds](integration_clouds.md).
* [Integration with Veeam ONE](integration_one.md).
* [Integration with VCSP Pulse](integration_pulse.md).

* [Integration with ConnectWise Manage](integration_cwm.md).

* Integration with Veeam backup agents. For details, see [Managing Veeam Backup Agents](manage_backup_agents.md).
* [Integration with custom plugins](integration_custom.md).
* Integration with Grafana for Veeam Service Provider Console RESTful API v3. For details, see section [Integration with Grafana](https://helpcenter.veeam.com/docs/vac/rest/grafana.html) of the REST API Reference.

If you want to manage Veeam ONE and Veeam Backup for Microsoft 365 servers hosted in client infrastructure, you must deploy Veeam Service Provider Console management agents on these servers. For details, see [Deploying Veeam Service Provider Console Management Agents](install_management_agents.md).

Required Privileges

To perform the task, a user must have one of the following roles assigned: Portal Administrator, Site Administrator, Portal Operator, Read-only User.

Site Administrator cannot connect and disconnect Veeam Cloud Connect servers.

Portal Operator and Read-only User can access only the Tenants tab of the Veeam Cloud Connect plugin. Read-only User can only export cloud tenant details. Portal Operator can manage cloud tenants but cannot create, assign or remove cloud tenants.


