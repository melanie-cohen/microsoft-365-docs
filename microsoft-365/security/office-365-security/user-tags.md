---
title: "User tags in Office 365 ATP"
f1.keywords:
- NOCSH
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date:
audience: ITPro
ms.topic: how-to
ms.service: O365-seccomp
localization_priority: Normal
search.appverid:
- MET150
ms.collection:
- M365-security-compliance
description: "Admins can learn how to identify specific groups of users with user tags in Office 365 ATP Plan 2. Tag filtering is available across alerts, reports, and investigations in Office 365 ATP to quickly identify the tagged users."
---

# User tags in Office 365 ATP

User tags are identifiers for specific groups of users in [Office 365 Advanced Threat Protection (ATP)](office-365-atp.md). [Priority accounts](https://docs.microsoft.com/microsoft-365/admin/setup/priority-accounts) are a type of user tag. If your organization has Office 365 ATP Plan 2 (included in your subscription or as an add-on), you can create custom user tags in addition to using the priority accounts tag.

After you apply tags to specific users, you can use those tags as filters in alerts, reports, and investigations:

- [Alerts in the Security & Compliance Center](alerts.md)
- [Threat Explorer and real-time detections](threat-explorer.md)
- [Threat protection status report](view-email-security-reports.md#threat-protection-status-report)
- [Campaign Views](campaigns.md)

This article explains how to configure user tags in the Security & Compliance Center. There are no cmdlets in Security & Compliance Center to manage user tags.

## What do you need to know before you begin?

- You open the Security & Compliance Center at <https://protection.office.com/>. To go directly to the **User tags** page, open <https://protection.office.com/userTags>.

- To create, modify, or remove user tags, you need to be a member of the **Global admin** or **Exchange admin** roles. For more information, see [Commonly used Microsoft 365 admin center roles](https://docs.microsoft.com/en-us/microsoft-365/admin/add-users/about-admin-roles?view=o365-worldwide#commonly-used-microsoft-365-admin-center-roles).

- You can also manage and monitor priority accounts in the Microsoft 365 admin center. For instructions, see [Manage and monitor priority accounts](https://docs.microsoft.com/microsoft-365/admin/setup/priority-accounts).

## Use the Security Center to create user tags

1. In the Security Center, go to **Threat management** \> **User tags**.

2. On the **User tags** page that opens, click **Create tag**.

3. The **Create tag** wizard opens in a new fly out. On the **Define tag** page, configure the following settings:

   - **Name**: Enter a unique, descriptive name for the tag. This is the value that you'll see and use.

   - **Description**: Enter an optional description for the tag.

   When you're finished, click **Next**.

4. On the **Assign mailboxes** page, do either of the following steps:

   - Click **Add mailboxes**. In the fly out that appears, do any of the following steps to add individual users or groups:

     - Click in the box and scroll through the list to select a user or group.
     - Click in the box and start typing to filter the list and select a user or group.
     - To add additional values, click in an empty area in the box.
     - To remove individual entries from the box, click **Remove** ![Remove icon](../../media/scc-remove-icon.png) on the user or group in the box.
     - To remove existing entries from the list below the box, click **Remove** ![Remove icon](../../media/scc-remove-icon.png) the entry.

     When you're finished, click **Add**.

   - Click **Import** to select a text file that contains the email addresses of the users or groups. Be sure the text file contains one entry per line.

   When you're finished, click **Next**.

5. On the **Review tag** page, review your settings. You can click **Edit** in the specific section to make changes.

   When you're finished, click **Submit**.

## Use the Security Center to view user tags

1. In the Security Center, go to **Threat management** \> **User tags**.

2. On the **User tags** page that opens, select the user tag that you want to view (don't click on the checkbox).

3. In the read-only details fly out that appears, review the settings.

   When you're finished, click **Close**.

## Use the Security Center to modify user tags

1. In the Security Center, go to **Threat management** \> **User tags**.

2. On the **User tags** page that opens, select the user tag that you want to view, and then click **Edit tag**.

3. The policy wizard opens in an **Edit tag** fly out. Click **Next** to review and modify the settings.

   When you're finished, click **Submit**.

## Use the Security Center to remove user tags

**Note**: You can't remove the built-in **Priority account** tag.

1. In the Security Center, go to **Threat management** \> **User tags**.

2. On the **User tags** page that opens, select the user tag that you want to remove, click **Delete tag**, and then select **Yes, remove** in the warning that appears.
