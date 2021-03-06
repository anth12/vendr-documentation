---
title: AppliedDiscount
description: API reference for AppliedDiscount in Vendr, the eCommerce solution for Umbraco v8+
---
## AppliedDiscount

```csharp
public class AppliedDiscount : ValueObjectBase
```

**Inheritance**

* class [ValueObjectBase](../valueobjectbase/)

**Namespace**
* [Vendr.Core.Models](../)

### Constructors

#### AppliedDiscount (1 of 4)

```csharp
public AppliedDiscount(DiscountReadOnly discount, Price price)
```

---

#### AppliedDiscount (2 of 4)

```csharp
public AppliedDiscount(DiscountReadOnly discount, Price originalPrice, Price price)
```

---

#### AppliedDiscount (3 of 4)

```csharp
public AppliedDiscount(Guid discountId, string discountName, Price price)
```

---

#### AppliedDiscount (4 of 4)

```csharp
public AppliedDiscount(Guid discountId, string discountName, Price originalPrice, Price price)
```


### Properties

#### DiscountId

```csharp
public Guid DiscountId { get; }
```


---

#### DiscountName

```csharp
public string DiscountName { get; }
```


---

#### OriginalPrice

```csharp
public Price OriginalPrice { get; }
```


---

#### Price

```csharp
public Price Price { get; }
```


### Methods

#### DeepClone

```csharp
public override object DeepClone()
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
