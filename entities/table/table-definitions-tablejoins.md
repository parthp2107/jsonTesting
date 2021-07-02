# table-definitions-tablejoins

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/properties/joins
```

Details of other tables this table is frequently joined with

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Forbidden | none | [table.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/data/table.json) |

### joins Type

`object` \([Details](table-definitions-tablejoins.md)\)

## joins Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [startDate](table-definitions-tablejoins.md#startdate) | `string` | Optional | cannot be null | [Table entity](../../types/common/common-definitions-date.md) |
| [dayCount](table-definitions-tablejoins.md#daycount) | `integer` | Optional | cannot be null | [Table entity](table-definitions-tablejoins-properties-daycount.md) |
| [columnJoins](table-definitions-tablejoins.md#columnjoins) | `array` | Optional | cannot be null | [Table entity](table-definitions-tablejoins-properties-columnjoins.md) |

### startDate

Date in ISO 8601 format in UTC time. Example - '2018-11-13'

`startDate`

* is optional
* Type: `string`
* cannot be null
* defined in: [Table entity](../../types/common/common-definitions-date.md)

#### startDate Type

`string`

#### startDate Constraints

**date**: the string must be a date string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

### dayCount

`dayCount`

* is optional
* Type: `integer`
* cannot be null
* defined in: [Table entity](table-definitions-tablejoins-properties-daycount.md)

#### dayCount Type

`integer`

#### dayCount Default Value

The default value is:

```javascript
1
```

### columnJoins

`columnJoins`

* is optional
* Type: `object[]` \([Details](table-definitions-columnjoins.md)\)
* cannot be null
* defined in: [Table entity](table-definitions-tablejoins-properties-columnjoins.md)

#### columnJoins Type

`object[]` \([Details](table-definitions-columnjoins.md)\)

