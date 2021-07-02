# dailycount

## Daily count of some measurement Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/dailyCount.json
```

Type used for capturing and reporting daily count of some measurement, such as usage, joins

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [dailyCount.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/dailyCount.json) |

### Daily count of some measurement Type

`object` \([Daily count of some measurement](dailycount.md)\)

## Daily count of some measurement Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [count](dailycount.md#count) | `integer` | Required | cannot be null | [Daily count of some measurement](dailycount-properties-count.md) |
| [date](dailycount.md#date) | `string` | Required | cannot be null | [Daily count of some measurement](../common/common-definitions-date.md) |

### count

Daily count of a measurement on the given date

`count`

* is required
* Type: `integer`
* cannot be null
* defined in: [Daily count of some measurement](dailycount-properties-count.md)

#### count Type

`integer`

#### count Constraints

**minimum**: the value of this number must greater than or equal to: `0`

### date

Date in ISO 8601 format in UTC time. Example - '2018-11-13'

`date`

* is required
* Type: `string`
* cannot be null
* defined in: [Daily count of some measurement](../common/common-definitions-date.md)

#### date Type

`string`

#### date Constraints

**date**: the string must be a date string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

