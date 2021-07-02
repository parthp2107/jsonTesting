# classification-definitions-personaldata

## Untitled object in Data classification related types Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/classification.json#/properties/tags/items
```

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [classification.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/classification.json) |

### items Type

`object` \([Details](classification-definitions-personaldata.md)\)

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [name](classification-definitions-personaldata.md#name) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-name.md) |
| [documentation](classification-definitions-personaldata.md#documentation) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-documentation.md) |
| [piiType](classification-definitions-personaldata.md#piitype) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-piitype.md) |
| [personalDataType](classification-definitions-personaldata.md#personaldatatype) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-personaldatatype.md) |

### name

Name of PII tag

`name`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-name.md)

#### name Type

`string`

### documentation

Name of PII tag

`documentation`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-documentation.md)

#### documentation Type

`string`

### piiType

PII tag type

`piiType`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-piitype.md)

#### piiType Type

`string`

#### piiType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"NONE"` |  |
| `"NON_SENSITIVE"` |  |
| `"SENSITIVE"` |  |

### personalDataType

Personal data tag type

`personalDataType`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-personaldatatype.md)

#### personalDataType Type

`string`

#### personalDataType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"PERSONAL"` |  |
| `"SPECIAL_CATEGORY"` |  |

