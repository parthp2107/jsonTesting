# common-definitions-profile

## Untitled object in User entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/teams/user.json#/properties/profile
```

> Profile of a user, team, or an organization

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [user.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/entity/teams/user.json) |

### profile Type

`object` \([Details](common-definitions-profile.md)\)

## profile Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [email](common-definitions-profile.md#email) | `string` | Optional | cannot be null | [Common types](common-definitions-profile-properties-email.md) |
| [images](common-definitions-profile.md#images) | `object` | Optional | cannot be null | [Common types](common-definitions-imagelist.md) |

### email

`email`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-profile-properties-email.md)

#### email Type

`string`

#### email Constraints

**email**: the string must be an email address, according to [RFC 5322, section 3.4.1](https://tools.ietf.org/html/rfc5322)

### images

> Links to list of images of varying resolutions/sizes

`images`

* is optional
* Type: `object` \([Details](common-definitions-imagelist.md)\)
* cannot be null
* defined in: [Common types](common-definitions-imagelist.md)

#### images Type

`object` \([Details](common-definitions-imagelist.md)\)

