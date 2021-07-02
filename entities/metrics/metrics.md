# metrics

## Metrics entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/metrics.json
```

Entity that represents a Metrics

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [metrics.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/data/metrics.json) |

### Metrics entity Type

`object` \([Metrics entity](metrics.md)\)

## Metrics entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](metrics.md#id) | `string` | Required | cannot be null | [Metrics entity](../../types/common/common-definitions-uuid.md) |
| [name](metrics.md#name) | `string` | Required | cannot be null | [Metrics entity](metrics-properties-name.md) |
| [fullyQualifiedName](metrics.md#fullyqualifiedname) | `string` | Optional | cannot be null | [Metrics entity](metrics-properties-fullyqualifiedname.md) |
| [description](metrics.md#description) | `string` | Optional | cannot be null | [Metrics entity](metrics-properties-description.md) |
| [href](metrics.md#href) | `string` | Optional | cannot be null | [Metrics entity](../../types/common/common-definitions-href.md) |
| [owner](metrics.md#owner) | `object` | Optional | cannot be null | [Metrics entity](../../types/common/common-definitions-entityreference.md) |
| [service](metrics.md#service) | `object` | Required | cannot be null | [Metrics entity](../../types/common/common-definitions-entityreference.md) |
| [usageSummary](metrics.md#usagesummary) | `object` | Optional | cannot be null | [Metrics entity](../../types/common/common-definitions-usagedetails.md) |

### id

Unique id used to identify an entity

`id`

* is required
* Type: `string`
* cannot be null
* defined in: [Metrics entity](../../types/common/common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### name

Name that identifies the this metrics instance uniquely.

`name`

* is required
* Type: `string`
* cannot be null
* defined in: [Metrics entity](metrics-properties-name.md)

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### fullyQualifiedName

Unique name that identifies a metric in the format 'ServiceName.MetricName'

`fullyQualifiedName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Metrics entity](metrics-properties-fullyqualifiedname.md)

#### fullyQualifiedName Type

`string`

#### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### description

Description of metrics instance. What is has and how to use it

`description`

* is optional
* Type: `string`
* cannot be null
* defined in: [Metrics entity](metrics-properties-description.md)

#### description Type

`string`

### href

Link to the resource corresponding to this entity

> Link to the resource

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Metrics entity](../../types/common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### owner

Owner of this metrics

> Entity reference that includes entity ID and entity type

`owner`

* is optional
* Type: `object` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Metrics entity](../../types/common/common-definitions-entityreference.md)

#### owner Type

`object` \([Details](../../types/common/common-definitions-entityreference.md)\)

### service

Link to service where this metrics is hosted in

> Entity reference that includes entity ID and entity type

`service`

* is required
* Type: `object` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Metrics entity](../../types/common/common-definitions-entityreference.md)

#### service Type

`object` \([Details](../../types/common/common-definitions-entityreference.md)\)

### usageSummary

Latest usage information for this database

> Type used to return usage details

`usageSummary`

* is optional
* Type: `object` \([Details](../../types/common/common-definitions-usagedetails.md)\)
* cannot be null
* defined in: [Metrics entity](../../types/common/common-definitions-usagedetails.md)

#### usageSummary Type

`object` \([Details](../../types/common/common-definitions-usagedetails.md)\)

