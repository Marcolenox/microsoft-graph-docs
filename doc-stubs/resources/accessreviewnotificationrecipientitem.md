---
title: "accessReviewNotificationRecipientItem resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessReviewNotificationRecipientItem resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|notificationRecipientScope|[accessReviewNotificationRecipientScope](../resources/accessreviewnotificationrecipientscope.md)|**TODO: Add Description**|
|notificationTemplateType|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.accessReviewNotificationRecipientItem"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessReviewNotificationRecipientItem",
  "notificationTemplateType": "String",
  "notificationRecipientScope": {
    "@odata.type": "microsoft.graph.accessReviewNotificationRecipientScope"
  }
}
```

