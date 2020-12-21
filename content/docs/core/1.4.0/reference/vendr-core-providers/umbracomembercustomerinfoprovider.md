---
title: UmbracoMemberCustomerInfoProvider
description: API reference for UmbracoMemberCustomerInfoProvider in Vendr, the eCommerce solution for Umbraco v8+
---
## UmbracoMemberCustomerInfoProvider

```csharp
public class UmbracoMemberCustomerInfoProvider : IRegisteredCustomerInfoProvider
```

**Inheritance**

* interface [IRegisteredCustomerInfoProvider](../iregisteredcustomerinfoprovider/)

**Namespace**
* [Vendr.Core.Providers](../)

### Constructors

#### UmbracoMemberCustomerInfoProvider

```csharp
public UmbracoMemberCustomerInfoProvider(IMemberService memberService)
```


### Methods

#### GetRegisteredCustomerInfo

```csharp
public RegisteredCustomerInfo GetRegisteredCustomerInfo(string customerReference)
```


---

#### HasRegisteredCustomerInfo

```csharp
public bool HasRegisteredCustomerInfo(string customerReference)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->