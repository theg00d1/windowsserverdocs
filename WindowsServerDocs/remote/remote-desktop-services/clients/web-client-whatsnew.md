---
title: What's new for Remote Desktop web client?
description: Learn about recent changes to the Remote Desktop web client
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: remote-desktop-services
ms.tgt_pltfrm: na
ms.topic: article
author: lizap
manager: dongill
ms.author: elizapo
ms.date: 1/28/2019
ms.localizationpriority: medium
---
# What's new for the Remote Desktop web client?

We regularly update the [Remote Desktop web client](remote-desktop-web-client.md), adding new features and fixing issues. Check out the latest updates below.

## Updates for version 1.0.7
*Published date: 1/24/2019*

- Offline use is now supported.
- Improved rendering on non-Edge browsers.
- Implemented limit for feed retrieval retry attempts to prevent DoS.
- Fixed accessibility bugs, enabling users with visual disabilities to use the web client.
- Improved error messages displayed to the user for feed errors.
- Added Ctrl + Alt + End (Windows) and fn + control + option + delete (Mac) shortcuts to invoke Ctrl + Alt + Del in remote machine.
- Improved telemetry for crash events. 
- Improved our build pipeline and build tools.
- Various bug fixes.

## Updates for version 1.0.1
*Published date: 10/29/2018*

- Added an option to **Capture support information** on the About page to diagnose issues.
- InPrivate mode is now supported.
- Improved support for non-English keyboards.
- Fixed an issue where tooltips with non-English characters showed incorrectly.
- Fixed graphics rendering issue which affected Chrome users.
- Updated time zone redirection with full DST support.
- Improved the error message for out-of-memory error.
- Various bug fixes.

## Updates for version 1.0.0
*Published date: 07/16/2018*

- Remote Desktop web client is now generally available.
- Admins can globally turn off telemetry for the web client.
- Various bug fixes.

## Updates for version 0.9.0
*Published date: 07/05/2018*

- New sign in experience within the web client.
- No longer prompted for credentials when launching a desktop or app connection (Single sign on).
- Moved the web client to a new URL: **https://server_FQDN/RDWeb/webclient/index.html**
- Added time zone redirection.
- Various bug fixes.

## Updates for version 0.8.1
*Published date: 05/17/2018*

- Updates to address CredSSP encryption oracle remediation described in CVE-2018-0886.
- Fixed connection failures for some languages when printing is enabled.
- Improved error message when a gateway is not part of the deployment.
- **Help** and **Feedback** options were added.

## Updates for version 0.8.0
*Published date: 03/28/2018*

- Initial public preview release of the web client.
- Copy/paste text through the clipboard with **CTRL+C** and **CTRL+V**.
- Print to a PDF file.
- Localized in 18 languages.
 
