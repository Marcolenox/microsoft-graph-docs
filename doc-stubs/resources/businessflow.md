---
title: "businessFlow resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# businessFlow resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List businessFlows](../api/businessflow-list.md)|[businessFlow](../resources/businessflow.md) collection|Get a list of the [businessFlow](../resources/businessflow.md) objects and their properties.|
|[Create businessFlow](../api/approvalworkflowprovider-post-businessflows.md)|[businessFlow](../resources/businessflow.md)|Create a new [businessFlow](../resources/businessflow.md) object.|
|[Get businessFlow](../api/businessflow-get.md)|[businessFlow](../resources/businessflow.md)|Read the properties and relationships of a [businessFlow](../resources/businessflow.md) object.|
|[Update businessFlow](../api/businessflow-update.md)|[businessFlow](../resources/businessflow.md)|Update the properties of a [businessFlow](../resources/businessflow.md) object.|
|[Delete businessFlow](../api/businessflow-delete.md)|None|Deletes a [businessFlow](../resources/businessflow.md) object.|
|[recordDecisions](../api/businessflow-recorddecisions.md)|None|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|customData|String|**TODO: Add Description**|
|deDuplicationId|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|policy|[governancePolicy](../resources/governancepolicy.md)|**TODO: Add Description**|
|policyTemplateId|String|**TODO: Add Description**|
|recordVersion|String|**TODO: Add Description**|
|schemaId|String|**TODO: Add Description**|
|settings|[businessFlowSettings](../resources/businessflowsettings.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.businessFlow",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.businessFlow",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "deDuplicationId": "String",
  "schemaId": "String",
  "customData": "String",
  "recordVersion": "String",
  "policy": {
    "@odata.type": "microsoft.graph.governancePolicy"
  },
  "policyTemplateId": "String",
  "settings": {
    "@odata.type": "microsoft.graph.businessFlowSettings"
  }
}
```

