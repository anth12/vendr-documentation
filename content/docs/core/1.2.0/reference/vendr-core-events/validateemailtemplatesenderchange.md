---
title: ValidateEmailTemplateSenderChange
description: API reference for ValidateEmailTemplateSenderChange in Vendr, the eCommerce solution for Umbraco v8+
---
## ValidateEmailTemplateSenderChange

```csharp
public class ValidateEmailTemplateSenderChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../validationeventbase/)

**Namespace**
* [Vendr.Core.Events.Validation](../)

### Constructors

#### ValidateEmailTemplateSenderChange

```csharp
public ValidateEmailTemplateSenderChange(EmailTemplateReadOnly emailTemplate, 
    ChangingValue<string> senderName, ChangingValue<string> senderEmail)
```


### Properties

#### EmailTemplate

```csharp
public EmailTemplateReadOnly EmailTemplate { get; }
```


---

#### SenderEmail

```csharp
public ChangingValue<string> SenderEmail { get; }
```


---

#### SenderName

```csharp
public ChangingValue<string> SenderName { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Core.dll -->
