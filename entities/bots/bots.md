# bots

## Bot entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/bots.json
```

Bot entity to capture the details of a bot

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [bots.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/bots.json) |

### Bot entity Type

`object` \([Bot entity](bots.md)\)

## Bot entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](bots.md#id) | `string` | Optional | cannot be null | [Bot entity](../../types/common/common-definitions-uuid.md) |
| [name](bots.md#name) | `string` | Optional | cannot be null | [Bot entity](bots-properties-name.md) |
| [displayName](bots.md#displayname) | `string` | Optional | cannot be null | [Bot entity](bots-properties-displayname.md) |
| [description](bots.md#description) | `string` | Optional | cannot be null | [Bot entity](bots-properties-description.md) |
| [href](bots.md#href) | `string` | Optional | cannot be null | [Bot entity](../../types/common/common-definitions-href.md) |

### id

Unique id used to identify an entity

`id`

* is optional
* Type: `string`
* cannot be null
* defined in: [Bot entity](../../types/common/common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### name

Optional name that identifies this entity. Same as id if name is not available

`name`

* is optional
* Type: `string`
* cannot be null
* defined in: [Bot entity](bots-properties-name.md)

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### displayName

Name used for display purposes. Example 'FirstName LastName'

`displayName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Bot entity](bots-properties-displayname.md)

#### displayName Type

`string`

### description

Description of entity instance.

`description`

* is optional
* Type: `string`
* cannot be null
* defined in: [Bot entity](bots-properties-description.md)

#### description Type

`string`

### href

Link to the resource corresponding to this entity

> Link to the resource

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Bot entity](../../types/common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

