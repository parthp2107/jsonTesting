# common-definitions-entityreference

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/properties/database
```

Reference to Database that contains this table

> Entity reference that includes entity ID and entity type

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [table.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/entity/data/table.json) |

### database Type

`object` \([Details](common-definitions-entityreference.md)\)

## database Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](common-definitions-entityreference.md#id) | `string` | Required | cannot be null | [Common types](common-definitions-uuid.md) |
| [type](common-definitions-entityreference.md#type) | `string` | Required | cannot be null | [Common types](common-definitions-entityreference-properties-type.md) |
| [name](common-definitions-entityreference.md#name) | `string` | Optional | cannot be null | [Common types](common-definitions-entityreference-properties-name.md) |
| [description](common-definitions-entityreference.md#description) | `string` | Optional | cannot be null | [Common types](common-definitions-entityreference-properties-description.md) |
| [href](common-definitions-entityreference.md#href) | `string` | Optional | cannot be null | [Common types](common-definitions-href.md) |

### id

Unique id used to identify an entity

`id`

* is required
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### type

Entity type/class name - Examples: database, table, metrics, redshift, mysql, bigquery, snowflake...

`type`

* is required
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-entityreference-properties-type.md)

#### type Type

`string`

### name

Name of the entity instance

`name`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-entityreference-properties-name.md)

#### name Type

`string`

### description

Optional description of entity

`description`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-entityreference-properties-description.md)

#### description Type

`string`

### href

Link to the entity resource

> Link to the resource

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

