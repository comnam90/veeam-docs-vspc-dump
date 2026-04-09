---
title: "Changing Alarm Assignment Scope"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/assign_alarms.html"
last_updated: "2/24/2026"
product_version: "9.2.0.33215"
---

# Changing Alarm Assignment Scope


By default, alarms aimed to monitor client backup infrastructures are assigned to all resellers, companies and locations. If you do not want to check alarm conditions for a specific reseller, company or location, you can exclude this reseller, company or location from the alarm assignment scope. As a result, the alarm will never be triggered for the excluded reseller, company or location, even if the alarm conditions are met.

Required Privileges

To perform this task, a user must have the following role assigned: Portal Administrator.

Changing Alarm Assignment Scope

To change the assignment scope for one or more alarms:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click Templates.
3. Open the Predefined Alarms tab.
4. To narrow down the list of alarms, you can apply the following filters:

* Alarm — search alarms by name.
* Alarm type — limit the list of the alarms by type (Predefined, Custom).
* Category — limit the list of the alarms by alarm object category (Management agent, Veeam Agent, Company, Internal, Discovery rule, Reseller, Site, Veeam Backup & Replication (including public cloud backup), Veeam ONE, Veeam Backup for Microsoft 365).

1. Select one or more alarms in the list.
2. At the top of the list, click Assign.

Alternatively, you can right-click the necessary alarm and choose Assign.

1. In the Assign Alarm window, clear check boxes next to resellers, companies and locations that must be excluded from the alarm assignment scope.
2. Clear the All new containers check box if all new containers you create in future must be excluded from the alarm assignment scope.

Organization containers aggregate companies and resellers to simplify the configuration of the alarm assignment scope. Containers are created with Veeam Service Provider Console REST API and can include companies, resellers and other containers. For details on creating containers in Veeam Service Provider Console REST API, see section [Create Container](https://helpcenter.veeam.com/references/vac/9.2/rest/tag/Containers#operation/CreateOrgContainer) of the REST API Reference.

1. Clear the All new companies check box if all new companies you register for a reseller in future must be excluded from the alarm assignment scope.
2. Clear the All new resellers check box if all new resellers you register in future must be excluded from the alarm assignment scope.
3. Clear the All new locations check box if all new locations you create in future must be excluded from the alarm assignment scope.
4. Click Apply.

After you exclude a reseller, company or location from the alarm assignment scope, you can check the excluded objects. To do so, find the necessary alarm in the list and click the Review link in the Exclusions column. In the Assign Alarm window, you can check and modify the alarm assignment scope if required.


