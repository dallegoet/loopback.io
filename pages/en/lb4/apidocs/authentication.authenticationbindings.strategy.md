---
lang: en
title: 'API docs: authentication.authenticationbindings.strategy'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.authentication.authenticationbindings.strategy.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/authentication](./authentication.md) &gt; [AuthenticationBindings](./authentication.authenticationbindings.md) &gt; [STRATEGY](./authentication.authenticationbindings.strategy.md)

## AuthenticationBindings.STRATEGY variable

Key used to bind an authentication strategy to the context for the authentication function to use.

<b>Signature:</b>

```typescript
STRATEGY: BindingKey<AuthenticationStrategy | undefined>
```

## Example


```ts
server
  .bind(AuthenticationBindings.STRATEGY)
  .toProvider(MyAuthenticationStrategy);

```


