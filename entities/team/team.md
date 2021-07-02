# team

## Team entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/teams/team.json
```

Team entity

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [team.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/teams/team.json) |

### Team entity Type

`object` \([Team entity](team.md)\)

## Team entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](team.md#id) | `string` | Required | cannot be null | [Team entity](../../types/common/common-definitions-uuid.md) |
| [name](team.md#name) | `string` | Required | cannot be null | [Team entity](team-properties-name.md) |
| [displayName](team.md#displayname) | `string` | Optional | cannot be null | [Team entity](team-properties-displayname.md) |
| [description](team.md#description) | `string` | Optional | cannot be null | [Team entity](team-properties-description.md) |
| [href](team.md#href) | `string` | Required | cannot be null | [Team entity](../../types/common/common-definitions-href.md) |
| [profile](team.md#profile) | `object` | Optional | cannot be null | [Team entity](../../types/common/common-definitions-profile.md) |
| [deleted](team.md#deleted) | `boolean` | Optional | cannot be null | [Team entity](team-properties-deleted.md) |
| [users](team.md#users) | `array` | Optional | cannot be null | [Team entity](../../types/common/common-definitions-entityreferencelist.md) |
| [owns](team.md#owns) | `array` | Optional | cannot be null | [Team entity](../../types/common/common-definitions-entityreferencelist.md) |

### id

Unique id used to identify an entity

`id`

* is required
* Type: `string`
* cannot be null
* defined in: [Team entity](../../types/common/common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### name

Unique name that identifies the team

`name`

* is required
* Type: `string`
* cannot be null
* defined in: [Team entity](team-properties-name.md)

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

### displayName

Name used for display purposes. Example 'Data Science team'

`displayName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Team entity](team-properties-displayname.md)

#### displayName Type

`string`

### description

Description of the team

`description`

* is optional
* Type: `string`
* cannot be null
* defined in: [Team entity](team-properties-description.md)

#### description Type

`string`

### href

Link to the resource corresponding to this entity

> Link to the resource

`href`

* is required
* Type: `string`
* cannot be null
* defined in: [Team entity](../../types/common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### profile

Team profile information

> Profile of a user, team, or an organization

`profile`

* is optional
* Type: `object` \([Details](../../types/common/common-definitions-profile.md)\)
* cannot be null
* defined in: [Team entity](../../types/common/common-definitions-profile.md)

#### profile Type

`object` \([Details](../../types/common/common-definitions-profile.md)\)

### deleted

`deleted`

* is optional
* Type: `boolean`
* cannot be null
* defined in: [Team entity](team-properties-deleted.md)

#### deleted Type

`boolean`

### users

Users that are part of the team

`users`

* is optional
* Type: `object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Team entity](../../types/common/common-definitions-entityreferencelist.md)

#### users Type

`object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)

### owns

Entities owned by the team

`owns`

* is optional
* Type: `object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Team entity](../../types/common/common-definitions-entityreferencelist.md)

#### owns Type

`object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)

