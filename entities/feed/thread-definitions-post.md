# thread-definitions-post

## Untitled object in Feed entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/feed/thread.json#/properties/posts/items
```

Post within a feed

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [thread.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/feed/thread.json) |

### items Type

`object` \([Details](thread-definitions-post.md)\)

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [message](thread-definitions-post.md#message) | `string` | Required | cannot be null | [Feed entity](thread-definitions-post-properties-message.md) |
| [postTs](thread-definitions-post.md#postts) | `string` | Optional | cannot be null | [Feed entity](thread-definitions-post-properties-postts.md) |
| [from](thread-definitions-post.md#from) | `string` | Required | cannot be null | [Feed entity](../../types/common/common-definitions-uuid.md) |

### message

Message in the post

`message`

* is required
* Type: `string`
* cannot be null
* defined in: [Feed entity](thread-definitions-post-properties-message.md)

#### message Type

`string`

### postTs

Timestamp of the post

`postTs`

* is optional
* Type: `string`
* cannot be null
* defined in: [Feed entity](thread-definitions-post-properties-postts.md)

#### postTs Type

`string`

#### postTs Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

### from

Unique id used to identify an entity

`from`

* is required
* Type: `string`
* cannot be null
* defined in: [Feed entity](../../types/common/common-definitions-uuid.md)

#### from Type

`string`

#### from Constraints

**UUID**: the string must be a UUID, according to [RFC 4122](https://tools.ietf.org/html/rfc4122)

