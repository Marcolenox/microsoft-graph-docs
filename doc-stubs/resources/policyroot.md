---
title: "policyRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# policyRoot resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List policyRoots](../api/policyroot-list.md)|[policyRoot](../resources/policyroot.md) collection|Get a list of the [policyRoot](../resources/policyroot.md) objects and their properties.|
|[Get policyRoot](../api/policyroot-get.md)|[policyRoot](../resources/policyroot.md)|Read the properties and relationships of a [policyRoot](../resources/policyroot.md) object.|
|[Update policyRoot](../api/policyroot-update.md)|[policyRoot](../resources/policyroot.md)|Update the properties of a [policyRoot](../resources/policyroot.md) object.|
|[Delete policyRoot](../api/policyroot-delete.md)|None|Deletes a [policyRoot](../resources/policyroot.md) object.|
|[List accessReviewPolicy](../api/policyroot-list-accessreviewpolicy.md)|[accessReviewPolicy](../resources/accessreviewpolicy.md) collection|Get the accessReviewPolicy resources from the accessReviewPolicy navigation property.|
|[Create accessReviewPolicy](../api/policyroot-post-accessreviewpolicy.md)|[accessReviewPolicy](../resources/accessreviewpolicy.md)|Create a new accessReviewPolicy object.|
|[List adminConsentRequestPolicy](../api/policyroot-list-adminconsentrequestpolicy.md)|[adminConsentRequestPolicy](../resources/adminconsentrequestpolicy.md) collection|Get the adminConsentRequestPolicy resources from the adminConsentRequestPolicy navigation property.|
|[Create adminConsentRequestPolicy](../api/policyroot-post-adminconsentrequestpolicy.md)|[adminConsentRequestPolicy](../resources/adminconsentrequestpolicy.md)|Create a new adminConsentRequestPolicy object.|
|[List directoryRoleAccessReviewPolicy](../api/policyroot-list-directoryroleaccessreviewpolicy.md)|[directoryRoleAccessReviewPolicy](../resources/directoryroleaccessreviewpolicy.md) collection|Get the directoryRoleAccessReviewPolicy resources from the directoryRoleAccessReviewPolicy navigation property.|
|[Create directoryRoleAccessReviewPolicy](../api/policyroot-post-directoryroleaccessreviewpolicy.md)|[directoryRoleAccessReviewPolicy](../resources/directoryroleaccessreviewpolicy.md)|Create a new directoryRoleAccessReviewPolicy object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessReviewPolicy|[accessReviewPolicy](../resources/accessreviewpolicy.md)|**TODO: Add Description**|
|adminConsentRequestPolicy|[adminConsentRequestPolicy](../resources/adminconsentrequestpolicy.md)|**TODO: Add Description**|
|directoryRoleAccessReviewPolicy|[directoryRoleAccessReviewPolicy](../resources/directoryroleaccessreviewpolicy.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.policyRoot",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.policyRoot"
}
```

