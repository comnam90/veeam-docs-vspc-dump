---
title: "How to Deploy Veeam Backup Agents in Offline Mode"
product: "vspc"
doc_type: "provider_admin"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_admin/install_agents_offline.html"
last_updated: "3/11/2026"
product_version: "9.2.0.33215"
---

# How to Deploy Veeam Backup Agents in Offline Mode


If the machine hosting Veeam Service Provider Console Server component has no connection to the internet, you can download Veeam backup agents setup files on machines with internet access and deliver them to the machine where Veeam Service Provider Console Server component is installed.

Step 1. Disable Automatic Product Updates

Before you install Veeam backup agents in the offline mode, you must disable product updates notifications and download:

1. At the top right corner of the Veeam Service Provider Console window, click Configuration.
2. In the configuration menu on the left, click About.
3. In the Product Updates & Download section, switch the Automatic checks (recommended) toggle to Off.

Alternatively, you can disable product updates notifications during Veeam Service Provider Console installation. For details, see section [Deploying Veeam Service Provider Console](https://helpcenter.veeam.com/docs/vac/deployment/deploy_vac.html?ver=9.2) of the Deployment Guide.

Step 2. Download Veeam Backup Agents Setup Files

Downloading Veeam Agent for Microsoft Windows

To download Veeam Agent for Microsoft Windows setup file:

1. Open Veeam Installation Server using the following address: https://vac.butler.veeam.com/api/v2/products/file/update?all=True&productName=vaw&vspcVersion=<vspc\_version>

where <vspc\_version> is the Veeam Service Provider Console build version.

1. For each URL address from the url parameters:

1. Copy URL address from the parameter.
2. Go to the copied address and save the downloaded file.

1. Copy the setup files to a location accessible from the machine where Veeam Service Provider Console Server component is installed.

Downloading Veeam Agent for Mac

To download Veeam Agent for Mac setup file:

1. Open Veeam Installation Server using the following address: https://vac.butler.veeam.com/api/v2/products/file/update?all=True&productName=vam&vspcVersion=<vspc\_version>

where <vspc\_version> is the Veeam Service Provider Console build version.

1. For each URL address from the url parameters:

1. Copy URL address from the parameter.
2. Go to the copied address and save the downloaded file.

1. Copy the setup files to a location accessible from the machine where Veeam Service Provider Console Server component is installed.

Downloading Veeam Agent for Linux

To download Veeam Agent for Linux setup files:

1. Open Veeam Installation Server using the following address: https://vac.butler.veeam.com/api/v2/products/file/update?all=True&productName=val&vspcVersion=<vspc\_version>

where <vspc\_version> is the Veeam Service Provider Console build version.

1. For all listed packages do the following:

1. Copy URL address from the url parameter.
2. Go to the copied address and save the downloaded file.

1. Create a <val\_version> folder with subfolders x86 and x64

where <val\_version> is the value from the version parameter.

1. Move the following files to the \<val\_version>\x86\ folder:

* blksnap-<val\_version>-1.noarch.rpm
* blksnap-<val\_version>-sle.noarch.rpm
* blksnap-ueficert-<val\_version>-1.noarch.rpm
* blksnap\_<val\_version>\_all.deb
* kmod-veeamsnap-<val\_version>-2.6.32\_131.0.15.el6.i386.rpm
* veeam-<val\_version>-1.el6.i386.rpm
* veeam-nosnap-<val\_version>-1.el6.i386.rpm
* veeam-nosnap\_<val\_version>\_i386.deb
* veeamsnap-<val\_version>-1.noarch.rpm
* veeamsnap-<val\_version>-1.sle.noarch.rpm
* veeamsnap-ueficert-<val\_version>-1.noarch.rpm
* veeamsnap\_<val\_version>\_all.deb
* veeam\_<val\_version>\_i386.deb

where <val\_version> is the value from the version parameter.

1. Move the remaining files except for the ValPackageIndex.xml to the \<val\_version>\x64\ folder.
2. Copy the <val\_version> folder and the ValPackageIndex.xml file to a location accessible from the machine where Veeam Service Provider Console Server component is installed.

Step 3. Install Veeam Backup Agents

1. Log on to the machine hosting Veeam Service Provider Console Server component.
2. In the <path>\ApplicationServer\ folder, create a new folder PackageOverride,

where <path> is the path to the directory where Veeam Service Provider Console is installed.

1. In the PackageOverride folder, create new folders for Veeam backup agents setup files:

* VAW — for Veeam Agent for Microsoft Windows

In the VAW folder, create a new x64 folder.

* VAL — for Veeam Agent for Linux
* VAM — for Veeam Agent for Mac

1. Copy agent setup files to the created folders:

* VeeamAgentWindows.exe and VeeamAgentWindows.exe.vsentry — to the VAW\x64 folder
* <val\_version> folder and ValPackageIndex.xml file — to the VAL folder

where <val\_version> is the value from the version parameter of the downloaded Veeam Agent for Linux setup files.

* Veeam Agent for Mac-<vam\_version>.pkg and Veeam Agent for Mac-<vam\_version>.pkg.vsentry  — to the VAM folder

where <vam\_version> is the value from the version parameter of the downloaded Veeam Agent for Mac setup package.

1. Restart Veeam Management Portal service.


