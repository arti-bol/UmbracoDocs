---
title: CountryMapper
description: API reference for CountryMapper in Umbraco Commerce
---
## CountryMapper

```csharp
public static class CountryMapper
```

**Namespace**
* [Umbraco.Commerce.Cms.Web.Models.Mappers](README.md)

### Methods

#### CountryEntitiesToBasicDtos

```csharp
public static IEnumerable<CountryBasicDto> CountryEntitiesToBasicDtos(
    IEnumerable<CountryReadOnly> entities)
```


---

#### CountryEntitiesToBasicDtos&lt;TDto&gt;

```csharp
public static IEnumerable<TDto> CountryEntitiesToBasicDtos<TDto>(
    IEnumerable<CountryReadOnly> entities)
    where TDto : CountryBasicDto, new()
```


---

#### CountryEntityToBasicDto&lt;TDto&gt;

```csharp
public static TDto CountryEntityToBasicDto<TDto>(CountryReadOnly entity, TDto dto = default(TDto))
    where TDto : CountryBasicDto, new()
```


---

#### CountryEntityToEditDto

```csharp
public static CountryEditDto CountryEntityToEditDto(CountryReadOnly entity, 
    CountryEditDto dto = null)
```


---

#### CountrySaveDtoToEntity

```csharp
public static Country CountrySaveDtoToEntity(CountrySaveDto dto, Country entity)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->