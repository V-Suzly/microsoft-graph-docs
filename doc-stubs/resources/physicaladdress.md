---
title: "physicalAddress resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# physicalAddress resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|city|String|**TODO: Add Description**|
|countryOrRegion|String|**TODO: Add Description**|
|postalCode|String|**TODO: Add Description**|
|postOfficeBox|String|**TODO: Add Description**|
|state|String|**TODO: Add Description**|
|street|String|**TODO: Add Description**|
|type|physicalAddressType|**TODO: Add Description**. Possible values are: `unknown`, `home`, `business`, `other`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.physicalAddress"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.physicalAddress",
  "type": "String",
  "postOfficeBox": "String",
  "street": "String",
  "city": "String",
  "state": "String",
  "countryOrRegion": "String",
  "postalCode": "String"
}
```
