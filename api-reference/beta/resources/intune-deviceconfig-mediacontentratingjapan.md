---
title: "mediaContentRatingJapan resource type"
description: "Not yet documented"
author: "tfitzmac"
localization_priority: Normal
ms.prod: "intune"
---

# mediaContentRatingJapan resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Not yet documented
## Properties
|Property|Type|Description|
|:---|:---|:---|
|movieRating|[ratingJapanMoviesType](../resources/intune-deviceconfig-ratingjapanmoviestype.md)|Movies rating selected for Japan. Possible values are: `allAllowed`, `allBlocked`, `general`, `parentalGuidance`, `agesAbove15`, `agesAbove18`.|
|tvRating|[ratingJapanTelevisionType](../resources/intune-deviceconfig-ratingjapantelevisiontype.md)|TV rating selected for Japan. Possible values are: `allAllowed`, `allBlocked`, `explicitAllowed`.|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.mediaContentRatingJapan"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.mediaContentRatingJapan",
  "movieRating": "String",
  "tvRating": "String"
}
```





