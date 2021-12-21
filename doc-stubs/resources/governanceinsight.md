---
title: "governanceInsight resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# governanceInsight resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**
This is an abstract type.

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List governanceInsights](../api/governanceinsight-list.md)|[governanceInsight](../resources/governanceinsight.md) collection|Get a list of the [governanceInsight](../resources/governanceinsight.md) objects and their properties.|
|[Create governanceInsight](../api/accessreviewinstancedecisionitem-post-insights.md)|[governanceInsight](../resources/governanceinsight.md)|Create a new [governanceInsight](../resources/governanceinsight.md) object.|
|[Get governanceInsight](../api/governanceinsight-get.md)|[governanceInsight](../resources/governanceinsight.md)|Read the properties and relationships of a [governanceInsight](../resources/governanceinsight.md) object.|
|[Update governanceInsight](../api/governanceinsight-update.md)|[governanceInsight](../resources/governanceinsight.md)|Update the properties of a [governanceInsight](../resources/governanceinsight.md) object.|
|[Delete governanceInsight](../api/governanceinsight-delete.md)|None|Deletes a [governanceInsight](../resources/governanceinsight.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|insightCreatedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.governanceInsight",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.governanceInsight",
  "id": "String (identifier)",
  "insightCreatedDateTime": "String (timestamp)"
}
```

