---
lang: en
title: 'API docs: repository.normalizekey'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.normalizekey.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [normalizeKey](./repository.normalizekey.md)

## normalizeKey() function

Workaround for MongoDB, where the connector returns ObjectID values even for properties configured with "type: string".

<b>Signature:</b>

```typescript
export declare function normalizeKey(rawKey: unknown): unknown;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  rawKey | <code>unknown</code> |  |

<b>Returns:</b>

`unknown`


