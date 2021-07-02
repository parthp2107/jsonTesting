# common-definitions-usagestats

## Untitled object in Common types Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/common.json#/definitions/usageDetails/properties/monthlyStats
```

> Type used to return usage statistics

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Forbidden | none | [common.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/common.json) |

### monthlyStats Type

`object` \([Details](common-definitions-usagestats.md)\)

## monthlyStats Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [count](common-definitions-usagestats.md#count) | `integer` | Required | cannot be null | [Common types](common-definitions-usagestats-properties-count.md) |
| [percentileRank](common-definitions-usagestats.md#percentilerank) | `number` | Optional | cannot be null | [Common types](common-definitions-usagestats-properties-percentilerank.md) |

### count

`count`

* is required
* Type: `integer`
* cannot be null
* defined in: [Common types](common-definitions-usagestats-properties-count.md)

#### count Type

`integer`

#### count Constraints

**minimum**: the value of this number must greater than or equal to: `0`

### percentileRank

`percentileRank`

* is optional
* Type: `number`
* cannot be null
* defined in: [Common types](common-definitions-usagestats-properties-percentilerank.md)

#### percentileRank Type

`number`

#### percentileRank Constraints

**maximum**: the value of this number must smaller than or equal to: `100`

**minimum**: the value of this number must greater than or equal to: `0`

