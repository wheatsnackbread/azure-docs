---
title: Azure API Management policy reference - redirect-content-urls | Microsoft Docs
description: Reference for the redirect-content-urls policy available for use in Azure API Management. Provides policy usage, settings, and examples.
services: api-management
author: dlepow

ms.service: azure-api-management
ms.topic: article
ms.date: 03/18/2024
ms.author: danlep
---

# Mask URLs in content

[!INCLUDE [api-management-availability-all-tiers](../../includes/api-management-availability-all-tiers.md)]

The `redirect-content-urls` policy rewrites (masks) links in the response body so that they point to the equivalent link via the gateway. Use in the outbound section to rewrite response body links to the backend service to make them point to the gateway. Use in the inbound section for an opposite effect.

> [!NOTE]
>  This policy does not change any header values such as `Location` headers. To change header values, use the [set-header](set-header-policy.md) policy.

[!INCLUDE [api-management-policy-generic-alert](../../includes/api-management-policy-generic-alert.md)]

## Policy statement

```xml
<redirect-content-urls />
```

## Usage

- [**Policy sections:**](./api-management-howto-policies.md#sections) inbound, outbound
- [**Policy scopes:**](./api-management-howto-policies.md#scopes) global, workspace, product, API, operation
-  [**Gateways:**](api-management-gateways-overview.md) classic, v2, consumption, self-hosted

### Usage notes

- This policy can only be used once in a policy section.


## Example

```xml
<redirect-content-urls />
```

## Related policies

* [Transformation](api-management-policies.md#transformation)

[!INCLUDE [api-management-policy-ref-next-steps](../../includes/api-management-policy-ref-next-steps.md)]
