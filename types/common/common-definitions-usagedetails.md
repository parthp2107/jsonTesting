# common-definitions-usagedetails

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/properties/usageSummary
```

Latest usage information for this table

> Type used to return usage details

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [table.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/entity/data/table.json) |

### usageSummary Type

`object` \([Details](common-definitions-usagedetails.md)\)

## usageSummary Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [dailyStats](common-definitions-usagedetails.md#dailystats) | `object` | Required | cannot be null | [Common types](common-definitions-usagestats.md) |
| [weeklyStats](common-definitions-usagedetails.md#weeklystats) | `object` | Optional | cannot be null | [Common types](common-definitions-usagestats.md) |
| [monthlyStats](common-definitions-usagedetails.md#monthlystats) | `object` | Optional | cannot be null | [Common types](common-definitions-usagestats.md) |
| [date](common-definitions-usagedetails.md#date) | `string` | Required | cannot be null | [Common types](common-definitions-date.md) |

### dailyStats

> Type used to return usage statistics

`dailyStats`

* is required
* Type: `object` \([Details](common-definitions-usagestats.md)\)
* cannot be null
* defined in: [Common types](common-definitions-usagestats.md)

#### dailyStats Type

`object` \([Details](common-definitions-usagestats.md)\)

### weeklyStats

> Type used to return usage statistics

`weeklyStats`

* is optional
* Type: `object` \([Details](common-definitions-usagestats.md)\)
* cannot be null
* defined in: [Common types](common-definitions-usagestats.md)

#### weeklyStats Type

`object` \([Details](common-definitions-usagestats.md)\)

### monthlyStats

> Type used to return usage statistics

`monthlyStats`

* is optional
* Type: `object` \([Details](common-definitions-usagestats.md)\)
* cannot be null
* defined in: [Common types](common-definitions-usagestats.md)

#### monthlyStats Type

`object` \([Details](common-definitions-usagestats.md)\)

### date

Date in ISO 8601 format in UTC time. Example - '2018-11-13'

`date`

* is required
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-date.md)

#### date Type

`string`

#### date Constraints

**date**: the string must be a date string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339)

