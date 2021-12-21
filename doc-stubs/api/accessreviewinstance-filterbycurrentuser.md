---
title: "accessReviewInstance: filterByCurrentUser"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# accessReviewInstance: filterByCurrentUser
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

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
GET /user/pendingAccessReviewInstances/filterByCurrentUser
```

## Function parameters
In the request URL, provide the following query parameters with values.
The following table shows the parameters that can be used with this function.

|Parameter|Type|Description|
|:---|:---|:---|
|on|accessReviewInstanceFilterByCurrentUserOptions|**TODO: Add Description**|


## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this function returns a `200 OK` response code and a [accessReviewInstance](../resources/accessreviewinstance.md) collection in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "accessreviewinstance_filterbycurrentuser"
}
-->
``` http
GET https://graph.microsoft.com/beta/user/pendingAccessReviewInstances/filterByCurrentUser(on='parameterValue')
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.accessReviewInstance)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.accessReviewInstance",
      "id": "String (identifier)",
      "startDateTime": "String (timestamp)",
      "endDateTime": "String (timestamp)",
      "errors": [
        {
          "@odata.type": "microsoft.graph.accessReviewError"
        }
      ],
      "status": "String",
      "scope": {
        "@odata.type": "microsoft.graph.accessReviewScope"
      },
      "reviewers": [
        {
          "@odata.type": "microsoft.graph.accessReviewReviewerScope"
        }
      ],
      "fallbackReviewers": [
        {
          "@odata.type": "microsoft.graph.accessReviewReviewerScope"
        }
      ],
      "customData": {
        "@odata.type": "microsoft.graph.accessReviewCustomData"
      },
      "isDraft": "Boolean"
    }
  ]
}
```

