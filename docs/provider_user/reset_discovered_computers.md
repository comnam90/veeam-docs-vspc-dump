---
title: "Resetting Discovered Computers"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/reset_discovered_computers.html"
last_updated: "8/8/2025"
product_version: "9.1.0.30636"
---

# Resetting Discovered Computers


To remove from the Discovered Computers list computers that were found with a discovery rule, you can reset discovery results. For example, this can be required if you improperly configured a discovery rule, discovery results display more computers than expected, or discovery results include computers that must not be protected with Veeam backup agents.

When you perform reset for a discovery rule, computers discovered with this rule are removed from the discovered computers list. However, computers on which Veeam Service Provider Console management agents are already installed and configured to communicate with Veeam Service Provider Console will be moved to the list of computers discovered by the External Discovery rule.

To reset discovery results:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Rules.
2. Select one or more discovery rules in the list.
3. At the top of the discovery rules list, click Reset Discovered Computers.

The number of computers discovered with a rule will be set to zero, and computers that do not run management agents will be removed from the list of discovered computers.


