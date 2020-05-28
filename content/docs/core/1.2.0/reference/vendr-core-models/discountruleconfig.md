---
title: DiscountRuleConfig
description: API reference for DiscountRuleConfig in Vendr, the eCommerce solution for Umbraco v8+
---
## DiscountRuleConfig

```csharp
public class DiscountRuleConfig : ValueObjectBase
```

**Inheritance**

* class [ValueObjectBase](../valueobjectbase/)

**Namespace**
* [Vendr.Core.Models](../)

### Constructors

#### DiscountRuleConfig (1 of 2)

```csharp
public DiscountRuleConfig(string ruleProviderAlias, 
    IEnumerable<KeyValuePair<string, string>> settings)
```

---

#### DiscountRuleConfig (2 of 2)

```csharp
public DiscountRuleConfig(string ruleProviderAlias, 
    IEnumerable<KeyValuePair<string, string>> settings, IEnumerable<DiscountRuleConfig> children)
```


### Properties

#### Children

```csharp
public IReadOnlyCollection<DiscountRuleConfig> Children { get; }
```


---

#### RuleProviderAlias

```csharp
public string RuleProviderAlias { get; }
```


---

#### Settings

```csharp
public IReadOnlyDictionary<string, string> Settings { get; }
```


### Methods

#### DeepClone

```csharp
public override object DeepClone()
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->