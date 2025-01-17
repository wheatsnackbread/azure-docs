---
title: External attack surface management in Defender for Cloud
description: Learn about Defender for Cloud integration with Defender External attack surface management to enhance security and reduce the risk of attacks.
ms.topic: concept-article
ms.date: 07/03/2024
#customer intent: As a reader, I want to learn about the integration between Defender for Cloud and Defender External attack surface management so that I can enhance my organization's security.
---

# External attack surface management in Defender for Cloud

Microsoft Defender for Cloud has the capability to perform external attack surface management, (outside-in) scans on multicloud environments. Defender for Cloud accomplishes this through its integration with [Microsoft Defender External Attack Surface Management](../external-attack-surface-management/overview.md). The integration allows organizations to improve their security posture while reducing the potential risk of being attacked by exploring their external attack surface. The integration is included with the Defender Cloud Security Posture Management (CSPM) plan by default and doesn't require a license from Defender External Attack Surface Management or any special configurations.

Defender External Attack Surface Management applies Microsoft’s crawling technology to discover assets that are related to your known online infrastructure, and actively scans these assets to discover new connections over time. Attack Surface Insights are generated by applying vulnerability and infrastructure data to showcase the key areas of concern for your organization, such as:

- Discover digital assets, always-on inventory.
- Analyze and prioritize risks and threats.
- Pinpoint attacker-exposed weaknesses, anywhere and on-demand.
- Gain visibility into third-party attack surfaces.

With this information, security and IT teams are able to identify unknowns, prioritize risks, eliminate threats, and extend vulnerability and exposure control beyond the firewall. The attack surface is made up of all the points of access that an unauthorized person could use to enter their system. The larger your attack surface is, the harder it's to protect.

External Attack Surface Management collects data on publicly exposed assets (“outside-in”) which Defender for Cloud's  Cloud Security Posture Management (CSPM) (“inside-out”) plan uses to assist with internet-exposure validation and discovery capabilities.

Learn more about [Defender External Attack Surface Management](../external-attack-surface-management/overview.md).

## External Attack Surface Management capabilities in Defender CSPM

The [Defender CSPM](concept-cloud-security-posture-management.md) plan utilizes the data collected through the Defender External Attack Surface Management integration to provide the following capabilities within the Defender for Cloud portal:

- Discover of all the internet facing cloud resources through the use of an outside-in scan.
- Attack path analysis which finds all exploitable paths starting from internet exposed IPs.
- Custom queries that correlate all internet exposed IPs with the rest of Defender for Cloud data in the cloud security explorer.

:::image type="content" source="media/concept-easm/cloud-security-explorer.png" alt-text="Screenshot of the cloud security explorer page in the Defender for Cloud portal." lightbox="media/concept-easm/cloud-security-explorer.png":::

## Related content
- [Detect internet exposed IP addresses](detect-exposed-ip-addresses.md)
- [Cloud security explorer and attack paths](concept-attack-path.md) in Defender for Cloud.
- [Deploy Defender External Attack Surface Management](../external-attack-surface-management/deploying-the-defender-easm-azure-resource.md).
