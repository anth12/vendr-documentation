---
title: ValidateGiftCardOrderChange
description: API reference for ValidateGiftCardOrderChange in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateGiftCardOrderChange

```csharp
public class ValidateGiftCardOrderChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateGiftCardOrderChange

```csharp
public ValidateGiftCardOrderChange(GiftCardReadOnly giftCard, ChangingValue<Guid?> orderId)
```


### Properties

#### GiftCard

```csharp
public GiftCardReadOnly GiftCard { get; }
```


---

#### OrderId

```csharp
public ChangingValue<Guid?> OrderId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
