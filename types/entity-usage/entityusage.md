# entityusage

## Usage details of an entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/entityUsage.json
```

Type used for capturing usage details of an entity

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [entityUsage.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/entityUsage.json) |

### Usage details of an entity Type

`object` \([Usage details of an entity](entityusage.md)\)

## Usage details of an entity Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [entity](entityusage.md#entity) | `object` | Required | cannot be null | [Usage details of an entity](../common/common-definitions-entityreference.md) |
| [usage](entityusage.md#usage) | `array` | Required | cannot be null | [Usage details of an entity](entityusage-properties-usage.md) |

### entity

Entity for which usage is returned

> Entity reference that includes entity ID and entity type

`entity`

* is required
* Type: `object` \([Details](../common/common-definitions-entityreference.md)\)
* cannot be null
* defined in: [Usage details of an entity](../common/common-definitions-entityreference.md)

#### entity Type

`object` \([Details](../common/common-definitions-entityreference.md)\)

### usage

List usage details per day

`usage`

* is required
* Type: `object[]` \([Details](../common/common-definitions-usagedetails.md)\)
* cannot be null
* defined in: [Usage details of an entity](entityusage-properties-usage.md)

#### usage Type

`object[]` \([Details](../common/common-definitions-usagedetails.md)\)

