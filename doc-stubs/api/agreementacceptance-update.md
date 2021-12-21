---
title: "Update agreementAcceptance"
description: "Update the properties of an agreementAcceptance object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update agreementAcceptance
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [agreementAcceptance](../resources/agreementacceptance.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /agreementAcceptances/{agreementAcceptancesId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
[!INCLUDE [table-intro](../../includes/update-property-table-intro.md)]


|Property|Type|Description|
|:---|:---|:---|
|agreementId|String|**TODO: Add Description** Optional.|
|userId|String|**TODO: Add Description** Optional.|
|deviceId|String|**TODO: Add Description** Optional.|
|deviceDisplayName|String|**TODO: Add Description** Optional.|
|deviceOSType|String|**TODO: Add Description** Optional.|
|deviceOSVersion|String|**TODO: Add Description** Optional.|
|agreementFileId|String|**TODO: Add Description** Optional.|
|userDisplayName|String|**TODO: Add Description** Optional.|
|userPrincipalName|String|**TODO: Add Description** Optional.|
|userEmail|String|**TODO: Add Description** Optional.|
|recordedDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|expirationDateTime|DateTimeOffset|**TODO: Add Description** Optional.|
|state|agreementAcceptanceState|**TODO: Add Description**. The possible values are: `accepted`, `declined`, `unknownFutureValue`. Optional.|



## Response

If successful, this method returns a `200 OK` response code and an updated [agreementAcceptance](../resources/agreementacceptance.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_agreementacceptance"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/agreementAcceptances/{agreementAcceptancesId}
Content-Type: application/json
Content-length: 470

{
  "@odata.type": "#microsoft.graph.agreementAcceptance",
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


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.agreementAcceptance",
  "id": "2bd00071-0071-2bd0-7100-d02b7100d02b",
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

