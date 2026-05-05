---
title: "Step 5. Choose Volumes to Back Up"
product: "vspc"
doc_type: "provider_user"
source_url: "https://helpcenter.veeam.com/docs/vac/provider_user/choose_volumes_lin.html"
last_updated: "5/4/2026"
product_version: "9.2.0.33215"
---

# Step 5. Choose Volumes to Back Up


The Volumes step of the wizard is available if at the [Backup Mode](choose_backup_mode_lin.md) step you have chosen to create a volume-level backup.

At this step of the wizard, you can define what volumes you want to include in the backup. The specified backup scope settings will apply to all computers that are added to the backup job.

To specify the backup scope:

1. At the top of the window, click New and select the type of objects that you want to include in the backup: Block devices, Mount points, LVM volumes or BTRFS subvolumes.
2. In the Add Object window, specify the path to the object that you want to back up and click OK.

You can specify the following objects to back up:

* Block devices. You can include in the backup scope all volumes on a computer disk or individual volumes of a protected computer:

* To include all volumes on a computer disk in the backup, type the path to a block device that represents the disk whose volumes you want to back up. For example: /dev/sda.
* To include a specific volume of a protected computer in the backup, type the path to a block device that represents the volume that you want to back up. For example: /dev/sda1.

|  |
| --- |
| Note: |
| If you include a block device in the backup, and this block device is a physical volume assigned to an LVM volume group, Veeam Agent for Linux will include the whole LVM volume group in the backup. |

* Mount points. You can include in the backup scope individual volumes of a protected computer. Type the path to a mount point of the volume that you want to back up. For example: / or /home.
* LVM volumes. You can include in the backup scope entire LVM volume groups or individual LVM logical volumes of a protected computer. Type the path to a mount point or a block device that represents the volume group or logical volume that you want to back up. For example: /dev/vg or /dev/vg/lv1.
* BTRFS subvolumes. You can include in the backup scope all BTRFS subvolumes of a BTRFS storage pool or specific BTRFS subvolumes.

* To include all subvolumes of a BTRFS pool in the backup, type the path to a block device that represents the BTRFS pool. For example: /dev/sda1.
* To include a specific BTRFS subvolume in the backup, type the path to a mount point of this subvolume. For example: /sub1.

1. Repeat steps 1–2 for all objects that you want to back up.

If you have created several system partitions, for example, a separate partition for the /boot directory, make sure that you include all of these partitions in the backup. Otherwise, Veeam Agent for Linux does not guarantee that the OS will boot properly when you attempt to recover from such backup.

[![Choose Volumes to Back Up](images/job_template_volumes_lin.webp)](images/job_template_volumes_lin.webp "Choose Volumes to Back Up")


