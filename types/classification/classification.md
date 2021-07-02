# classification

## Data classification related types Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/classification.json
```

Data classification related types

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | Yes | Unknown status | No | Forbidden | Allowed | none | [classification.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/classification.json) |

### Data classification related types Type

`object` \([Data classification related types](classification.md)\)

## Data classification related types Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [tags](classification.md#tags) | `array` | Optional | cannot be null | [Data classification related types](classification-properties-tags.md) |

### tags

`tags`

* is optional
* Type: `object[]` \([Details](classification-definitions-personaldata.md)\)
* cannot be null
* defined in: [Data classification related types](classification-properties-tags.md)

#### tags Type

`object[]` \([Details](classification-definitions-personaldata.md)\)

## Data classification related types Definitions

### Definitions group personalData

Reference this group by using

```javascript
{"$ref":"https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/classification.json#/definitions/personalData"}
```

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [name](classification.md#name) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-name.md) |
| [documentation](classification.md#documentation) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-documentation.md) |
| [piiType](classification.md#piitype) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-piitype.md) |
| [personalDataType](classification.md#personaldatatype) | `string` | Optional | cannot be null | [Data classification related types](classification-definitions-personaldata-properties-personaldatatype.md) |

#### name

Name of PII tag

`name`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-name.md)

**name Type**

`string`

#### documentation

Name of PII tag

`documentation`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-documentation.md)

**documentation Type**

`string`

#### piiType

PII tag type

`piiType`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-piitype.md)

**piiType Type**

`string`

**piiType Constraints**

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"NONE"` |  |
| `"NON_SENSITIVE"` |  |
| `"SENSITIVE"` |  |

#### personalDataType

Personal data tag type

`personalDataType`

* is optional
* Type: `string`
* cannot be null
* defined in: [Data classification related types](classification-definitions-personaldata-properties-personaldatatype.md)

**personalDataType Type**

`string`

**personalDataType Constraints**

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"PERSONAL"` |  |
| `"SPECIAL_CATEGORY"` |  |

