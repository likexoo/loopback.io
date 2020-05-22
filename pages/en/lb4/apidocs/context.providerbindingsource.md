---
lang: en
title: 'API docs: context.providerbindingsource'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/context
permalink: /doc/en/lb4/apidocs.context.providerbindingsource.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [ProviderBindingSource](./context.providerbindingsource.md)

## ProviderBindingSource type

Binding source for `toProvider`

<b>Signature:</b>

```typescript
export declare type ProviderBindingSource<T> = {
    type: BindingType.PROVIDER;
    value: Constructor<Provider<T>>;
};
```
