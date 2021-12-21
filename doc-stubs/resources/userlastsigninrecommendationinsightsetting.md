---
title: "userLastSignInRecommendationInsightSetting resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userLastSignInRecommendationInsightSetting resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [accessReviewRecommendationInsightSetting](../resources/accessreviewrecommendationinsightsetting.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|recommendationLookBackDuration|Duration|**TODO: Add Description**|
|signInScope|userSignInRecommendationScope|**TODO: Add Description**. The possible values are: `tenant`, `application`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.userLastSignInRecommendationInsightSetting"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userLastSignInRecommendationInsightSetting",
  "recommendationLookBackDuration": "String (duration)",
  "signInScope": "String"
}
```

