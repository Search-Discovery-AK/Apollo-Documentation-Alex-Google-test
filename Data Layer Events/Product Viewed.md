# Product Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "Product Viewed",
    "items": [
        {
            "item_brand": "<item_brand>",
            "item_id": "<item_id>",
            "item_name": "<item_name>",
            "item_variant": "<item_variant>"
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|item_brand|string|Item brand|Gucci|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_variant|string|The variant of the item.|Black|||||||



