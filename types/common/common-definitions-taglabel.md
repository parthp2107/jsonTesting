# common-definitions-taglabel

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/properties/tags/items
```

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [table.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/entity/data/table.json) |

### items Type

`object` \([Details](common-definitions-taglabel.md)\)

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [tagFQN](common-definitions-taglabel.md#tagfqn) | `string` | Optional | cannot be null | [Common types](common-definitions-taglabel-properties-tagfqn.md) |
| [labelType](common-definitions-taglabel.md#labeltype) | `string` | Optional | cannot be null | [Common types](common-definitions-taglabel-properties-labeltype.md) |
| [state](common-definitions-taglabel.md#state) | `string` | Optional | cannot be null | [Common types](common-definitions-taglabel-properties-state.md) |
| [href](common-definitions-taglabel.md#href) | `string` | Optional | cannot be null | [Common types](common-definitions-href.md) |

### tagFQN

`tagFQN`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-taglabel-properties-tagfqn.md)

#### tagFQN Type

`string`

#### tagFQN Constraints

**maximum length**: the maximum number of characters for this string is: `45`

### labelType

`labelType`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-taglabel-properties-labeltype.md)

#### labelType Type

`string`

#### labelType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"MANUAL"` |  |
| `"PROPAGATED"` |  |
| `"AUTOMATED"` |  |
| `"DERIVED"` |  |

#### labelType Default Value

The default value is:

```javascript
"MANUAL"
```

### state

`state`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-taglabel-properties-state.md)

#### state Type

`string`

#### state Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"SUGGESTED"` |  |
| `"CONFIRMED"` |  |

#### state Default Value

The default value is:

```javascript
"CONFIRMED"
```

### href

Link to the tag resource

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

