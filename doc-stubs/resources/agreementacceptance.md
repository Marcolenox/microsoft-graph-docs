---
title: "agreementAcceptance resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# agreementAcceptance resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List agreementAcceptances](../api/agreementacceptance-list.md)|[agreementAcceptance](../resources/agreementacceptance.md) collection|Get a list of the [agreementAcceptance](../resources/agreementacceptance.md) objects and their properties.|
|[Create agreementAcceptance](../api/agreementacceptance-post-agreementacceptances.md)|[agreementAcceptance](../resources/agreementacceptance.md)|Create a new [agreementAcceptance](../resources/agreementacceptance.md) object.|
|[Get agreementAcceptance](../api/agreementacceptance-get.md)|[agreementAcceptance](../resources/agreementacceptance.md)|Read the properties and relationships of an [agreementAcceptance](../resources/agreementacceptance.md) object.|
|[Update agreementAcceptance](../api/agreementacceptance-update.md)|[agreementAcceptance](../resources/agreementacceptance.md)|Update the properties of an [agreementAcceptance](../resources/agreementacceptance.md) object.|
|[Delete agreementAcceptance](../api/agreementacceptance-delete.md)|None|Deletes an [agreementAcceptance](../resources/agreementacceptance.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|agreementFileId|String|**TODO: Add Description**|
|agreementId|String|**TODO: Add Description**|
|deviceDisplayName|String|**TODO: Add Description**|
|deviceId|String|**TODO: Add Description**|
|deviceOSType|String|**TODO: Add Description**|
|deviceOSVersion|String|**TODO: Add Description**|
|expirationDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|recordedDateTime|DateTimeOffset|**TODO: Add Description**|
|state|agreementAcceptanceState|**TODO: Add Description**. The possible values are: `accepted`, `declined`, `unknownFutureValue`.|
|userDisplayName|String|**TODO: Add Description**|
|userEmail|String|**TODO: Add Description**|
|userId|String|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.agreementAcceptance",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.agreementAcceptance",
  "id": "String (identifier)",
  "agreementId": "String",
  "userId": "String",
  "deviceId": "String",
  "deviceDisplayName": "String",
  "deviceOSType": "String",
  "deviceOSVersion": "String",
  "agreementFileId": "String",
  "userDisplayName": "String",
  "userPrincipalName": "String",
  "userEmail": "String",
  "recordedDateTime": "String (timestamp)",
  "expirationDateTime": "String (timestamp)",
  "state": "String"
}
```

