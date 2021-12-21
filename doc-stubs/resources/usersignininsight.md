---
title: "userSignInInsight resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userSignInInsight resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [governanceInsight](../resources/governanceinsight.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userSignInInsights](../api/usersignininsight-list.md)|[userSignInInsight](../resources/usersignininsight.md) collection|Get a list of the [userSignInInsight](../resources/usersignininsight.md) objects and their properties.|
|[Get userSignInInsight](../api/usersignininsight-get.md)|[userSignInInsight](../resources/usersignininsight.md)|Read the properties and relationships of a [userSignInInsight](../resources/usersignininsight.md) object.|
|[Update userSignInInsight](../api/usersignininsight-update.md)|[userSignInInsight](../resources/usersignininsight.md)|Update the properties of a [userSignInInsight](../resources/usersignininsight.md) object.|
|[Delete userSignInInsight](../api/usersignininsight-delete.md)|None|Deletes a [userSignInInsight](../resources/usersignininsight.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [governanceInsight](../resources/governanceinsight.md).|
|insightCreatedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [governanceInsight](../resources/governanceinsight.md).|
|lastSignInDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userSignInInsight",
  "baseType": "microsoft.graph.governanceInsight",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userSignInInsight",
  "id": "String (identifier)",
  "insightCreatedDateTime": "String (timestamp)",
  "lastSignInDateTime": "String (timestamp)"
}
```

