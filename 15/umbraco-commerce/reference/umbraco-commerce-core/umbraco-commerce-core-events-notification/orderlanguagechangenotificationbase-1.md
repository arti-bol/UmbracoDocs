---
title: OrderLanguageChangeNotificationBase<TEntity>
description: API reference for OrderLanguageChangeNotificationBase<TEntity> in Umbraco Commerce
---
## OrderLanguageChangeNotificationBase&lt;TEntity&gt;

```csharp
public abstract class OrderLanguageChangeNotificationBase<TEntity> : 
    OrderNotificationEventBase<TEntity>
    where TEntity : OrderReadOnly
```

**Inheritance**

* Class [OrderNotificationEventBase&lt;TOrder&gt;](ordernotificationeventbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderLanguageChangeNotificationBase&lt;TEntity&gt;

```csharp
public OrderLanguageChangeNotificationBase(TEntity order, ChangingValue<string> languageIsoCode)
```


### Properties

#### LanguageIsoCode

```csharp
public ChangingValue<string> LanguageIsoCode { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->