---
title: ValidateCountryCodeChange
description: API reference for ValidateCountryCodeChange in Umbraco Commerce
---
## ValidateCountryCodeChange

```csharp
public class ValidateCountryCodeChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateCountryCodeChange

```csharp
public ValidateCountryCodeChange(CountryReadOnly country, ChangingValue<string> code)
```


### Properties

#### Code

```csharp
public ChangingValue<string> Code { get; }
```


---

#### Country

```csharp
public CountryReadOnly Country { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
