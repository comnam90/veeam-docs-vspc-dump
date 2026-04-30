---
title: "File Shares"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/export_file_share_jobs.html"
last_updated: "4/29/2026"
product_version: "9.2.0.33215"
---

# File Shares


To view and export file share job details:

1. Log in to Veeam Service Provider Console.

For details, see [Accessing Veeam Service Provider Console](access_vac.md).

1. In the menu on the left, click Backup Jobs.
2. Open the Data Backup tab and navigate to Virtual Infrastructure.

Veeam Service Provider Console will display a list of all file jobs configured on managed backup servers.

To narrow down the list of jobs, you can apply the following filters:

* Job — search jobs by job name.
* Server — search jobs by name of a file share server.
* Status — limit the list of jobs by the result of the latest job session (Success, Warning, Failed, Running, Information).
* Type — limit the list of jobs by type (File share backup, File share backup copy, File copy, File to tape).

* Location — limit the list of jobs by location to which jobs belong. To limit the list of jobs by location, use filter at the top left corner of the Veeam Service Provider Console window.

1. To export job details, click Export to and choose a format of the exported data:

* CSV — choose this option to structure exported data as a CSV file.
* XML — choose this option to structure exported data as an XML file.

The file with exported data will be saved to the default download location on your computer.

[![View File Share Job Details](images/view_file_share_jobs.webp)](images/view_file_share_jobs.webp "View File Share Job Details")

Each job in the list is described with a set of properties. By default, some properties in the list are hidden. To display additional properties, click the ellipsis on the right of the list header and choose job properties that must be displayed.

If a job is assigned to your company by the service provider, some properties may be unavailable.

* Job Status — status of the latest job session (Success, Warning, Failed, Running, No Info).
* Job — name of a data protection job.
* Backup Server — name of a backup server on which a job is configured.

* Location — name of a location to which a job belongs.
* Server — name of a file share server. If a job protects multiple file shares, this column displays the number of servers included in the job.

You can click this property, to view and export details of file shares included in a job. For details, see [File Share Details](export_file_share_jobs.md#details).

* Job Type — type of a file protection job (File share backup, File share backup copy, File copy, File to tape).
* Source Size — size of protected data at the source file share.
* Backed Up Files — percentage of files on a source server protected by a job.

You can click this property, to view and export details of file shares included in a job. For details, see [File Share Details](export_file_share_jobs.md#details).

* Destination — name of a target backup location.
* Last Run — amount of time since the latest job session started.
* Archive Repository — name of a backup repository where long-term backups are stored.
* Duration — time taken to complete the latest job session.
* Avg. Duration — average time a job session takes to complete (total duration of job sessions for the previous month divided by the number of job sessions for the previous month).
* Processing Rate — rate at which data was processed during the latest job session.
* Transferred Data — total amount of data that was transferred to target during the latest job session.
* Schedule — type of schedule configured for the job (Daily, Monthly, Periodically, Continuously, Chained, Not scheduled, Disabled).
* Bottleneck — bottleneck in the process of transferring the data from source to target (Source, Proxy, Network, Target).

File Share Details

The following details are available for protected file shares:

* Status — status of the latest file share job session.
* Server — name of a file share server.
* Files & Folders — number of files and folders included in a job.

Click this property to see the names of backup up items and applied file masks.

* N. of Files — number of files protected on a file share.
* Changed Files — number of files changed since the previous restore point was created for a file share.
* Transferred Files — percentage of changed files, that were successfully transferred to target during the latest job session.
* Duration — time taken to complete the latest job session.


