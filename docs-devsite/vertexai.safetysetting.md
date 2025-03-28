Project: /docs/reference/js/_project.yaml
Book: /docs/reference/_book.yaml
page_type: reference

{% comment %}
DO NOT EDIT THIS FILE!
This is generated by the JS SDK team, and any local changes will be
overwritten. Changes should be made in the source code at
https://github.com/firebase/firebase-js-sdk
{% endcomment %}

# SafetySetting interface
Safety setting that can be sent as part of request parameters.

<b>Signature:</b>

```typescript
export interface SafetySetting 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [category](./vertexai.safetysetting.md#safetysettingcategory) | [HarmCategory](./vertexai.md#harmcategory) |  |
|  [method](./vertexai.safetysetting.md#safetysettingmethod) | [HarmBlockMethod](./vertexai.md#harmblockmethod) |  |
|  [threshold](./vertexai.safetysetting.md#safetysettingthreshold) | [HarmBlockThreshold](./vertexai.md#harmblockthreshold) |  |

## SafetySetting.category

<b>Signature:</b>

```typescript
category: HarmCategory;
```

## SafetySetting.method

<b>Signature:</b>

```typescript
method?: HarmBlockMethod;
```

## SafetySetting.threshold

<b>Signature:</b>

```typescript
threshold: HarmBlockThreshold;
```
