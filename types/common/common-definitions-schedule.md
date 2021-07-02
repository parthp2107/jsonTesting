# common-definitions-schedule

## Untitled object in Database service entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/services/databaseService.json#/properties/ingestionSchedule
```

Schedule for running metadata ingestion jobs

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [databaseService.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/entity/services/databaseService.json) |

### ingestionSchedule Type

`object` \([Details](common-definitions-schedule.md)\)

## ingestionSchedule Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [startDate](common-definitions-schedule.md#startdate) | `string` | Optional | cannot be null | [Common types](common-definitions-datetime.md) |
| [repeatFrequency](common-definitions-schedule.md#repeatfrequency) | `string` | Optional | cannot be null | [Common types](common-definitions-duration.md) |

### startDate

Date and time in ISO 8601 format. Example - '2018-11-13T20:20:39+00:00'

`startDate`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-datetime.md)

#### startDate Type

`string`

#### startDate Constraints

**unknown format**: the value of this string must follow the format: `date-Time`

### repeatFrequency

Duration in ISO 8601 format in UTC time. Example - 'P23DT23H'

> Jsonschema does not handle ISO 8601 duration yet and hence no format for this type

`repeatFrequency`

* is optional
* Type: `string`
* cannot be null
* defined in: [Common types](common-definitions-duration.md)

#### repeatFrequency Type

`string`

