---
lang: en
title: 'API docs: metadata.decoratorfactory.duplicatedecorationerror'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.metadata.decoratorfactory.duplicatedecorationerror.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/metadata](./metadata.md) &gt; [DecoratorFactory](./metadata.decoratorfactory.md) &gt; [duplicateDecorationError](./metadata.decoratorfactory.duplicatedecorationerror.md)

## DecoratorFactory.duplicateDecorationError() method

Create an error to report if the decorator is applied to the target more than once

<b>Signature:</b>

```typescript
protected duplicateDecorationError(target: Object, member?: string | symbol, descriptorOrIndex?: TypedPropertyDescriptor<any> | number): Error;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  target | <code>Object</code> | Decoration target |
|  member | <code>string &#124; symbol</code> | Optional property or method |
|  descriptorOrIndex | <code>TypedPropertyDescriptor&lt;any&gt; &#124; number</code> | Optional parameter index or method descriptor |

<b>Returns:</b>

`Error`


