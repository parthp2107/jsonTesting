# table-definitions-columnjoins

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/definitions/tableJoins/properties/columnJoins/items
```

Information on other tables that this table column is frequently joined with

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Forbidden | none | [table.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/data/table.json) |

### items Type

`object` \([Details](table-definitions-columnjoins.md)\)

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [columnName](table-definitions-columnjoins.md#columnname) | `string` | Optional | cannot be null | [Table entity](table-definitions-columnname.md) |
| [joinedWith](table-definitions-columnjoins.md#joinedwith) | `array` | Optional | cannot be null | [Table entity](table-definitions-columnjoins-properties-joinedwith.md) |

### columnName

Local name \(not fully qualified name\) of the column

`columnName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-columnname.md)

#### columnName Type

`string`

#### columnName Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:

```text
^[^.]*$
```

[try pattern](https://regexr.com/?expression=%5E%5B%5E.%5D*%24)

### joinedWith

Fully qualified names of the columns that this column is joined with

`joinedWith`

* is optional
* Type: `object[]` \([Details](table-definitions-columnjoins-properties-joinedwith-items.md)\)
* cannot be null
* defined in: [Table entity](table-definitions-columnjoins-properties-joinedwith.md)

#### joinedWith Type

`object[]` \([Details](table-definitions-columnjoins-properties-joinedwith-items.md)\)

