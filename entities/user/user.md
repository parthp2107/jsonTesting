# user

## User entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/teams/user.json
```

User entity that is part of an organization

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [user.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/teams/user.json) |

### User entity Type

`object` \([User entity](user.md)\)

## User entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [id](user.md#id) | `string` | Required | cannot be null | [User entity](../../types/common/common-definitions-uuid.md) |
| [name](user.md#name) | `string` | Required | cannot be null | [User entity](user-properties-name.md) |
| [displayName](user.md#displayname) | `string` | Optional | cannot be null | [User entity](user-properties-displayname.md) |
| [href](user.md#href) | `string` | Required | cannot be null | [User entity](../../types/common/common-definitions-href.md) |
| [timezone](user.md#timezone) | `string` | Optional | cannot be null | [User entity](user-properties-timezone.md) |
| [deactivated](user.md#deactivated) | `boolean` | Optional | cannot be null | [User entity](user-properties-deactivated.md) |
| [isBot](user.md#isbot) | `boolean` | Optional | cannot be null | [User entity](user-properties-isbot.md) |
| [profile](user.md#profile) | `object` | Optional | cannot be null | [User entity](../../types/common/common-definitions-profile.md) |
| [teams](user.md#teams) | `array` | Optional | cannot be null | [User entity](../../types/common/common-definitions-entityreferencelist.md) |
| [owns](user.md#owns) | `array` | Optional | cannot be null | [User entity](../../types/common/common-definitions-entityreferencelist.md) |
| [follows](user.md#follows) | `array` | Optional | cannot be null | [User entity](../../types/common/common-definitions-entityreferencelist.md) |

### id

Unique id used to identify an entity

`id`

* is required
* Type: `string`
* cannot be null
* defined in: [User entity](../../types/common/common-definitions-uuid.md)

#### id Type

`string`

#### id Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

### name

Name that identifies the this entity instance uniquely. Same as id if when name is not unique

`name`

* is required
* Type: `string`
* cannot be null
* defined in: [User entity](user-properties-name.md)

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
* defined in: [User entity](user-properties-displayname.md)

#### displayName Type

`string`

### href

Link to the resource corresponding to this entity

> Link to the resource

`href`

* is required
* Type: `string`
* cannot be null
* defined in: [User entity](../../types/common/common-definitions-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### timezone

Timezone of the user

`timezone`

* is optional
* Type: `string`
* cannot be null
* defined in: [User entity](user-properties-timezone.md)

#### timezone Type

`string`

#### timezone Constraints

**unknown format**: the value of this string must follow the format: `timezone`

### deactivated

`deactivated`

* is optional
* Type: `boolean`
* cannot be null
* defined in: [User entity](user-properties-deactivated.md)

#### deactivated Type

`boolean`

### isBot

`isBot`

* is optional
* Type: `boolean`
* cannot be null
* defined in: [User entity](user-properties-isbot.md)

#### isBot Type

`boolean`

### profile

> Profile of a user, team, or an organization

`profile`

* is optional
* Type: `object` \([Details](../../types/common/common-definitions-profile.md)\)
* cannot be null
* defined in: [User entity](../../types/common/common-definitions-profile.md)

#### profile Type

`object` \([Details](../../types/common/common-definitions-profile.md)\)

### teams

Teams that the user belongs to

`teams`

* is optional
* Type: `object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [User entity](../../types/common/common-definitions-entityreferencelist.md)

#### teams Type

`object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)

### owns

Entities owned by the user

`owns`

* is optional
* Type: `object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [User entity](../../types/common/common-definitions-entityreferencelist.md)

#### owns Type

`object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)

### follows

Entities followed by the user

`follows`

* is optional
* Type: `object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [User entity](../../types/common/common-definitions-entityreferencelist.md)

#### follows Type

`object[]` \([Details](../../types/common/common-definitions-entityreference.md)\)

