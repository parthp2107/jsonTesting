# table-definitions-column

## Untitled object in Table entity Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/entity/data/table.json#/properties/columns/items
```

Type for capturing a column in a table

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [table.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Entities/out/entity/data/table.json) |

### items Type

`object` \([Details](table-definitions-column.md)\)

## items Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [name](table-definitions-column.md#name) | `string` | Required | cannot be null | [Table entity](table-definitions-columnname.md) |
| [columnDataType](table-definitions-column.md#columndatatype) | `string` | Required | cannot be null | [Table entity](table-definitions-columndatatype.md) |
| [description](table-definitions-column.md#description) | `string` | Optional | cannot be null | [Table entity](table-definitions-column-properties-description.md) |
| [fullyQualifiedName](table-definitions-column.md#fullyqualifiedname) | `string` | Optional | cannot be null | [Table entity](table-definitions-fullyqualifiedcolumnname.md) |
| [tags](table-definitions-column.md#tags) | `array` | Optional | cannot be null | [Table entity](table-definitions-column-properties-tags.md) |
| [columnConstraint](table-definitions-column.md#columnconstraint) | `string` | Optional | cannot be null | [Table entity](table-definitions-columnconstraint.md) |
| [ordinalPosition](table-definitions-column.md#ordinalposition) | `integer` | Optional | cannot be null | [Table entity](table-definitions-column-properties-ordinalposition.md) |

### name

Local name \(not fully qualified name\) of the column

`name`

* is required
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-columnname.md)

#### name Type

`string`

#### name Constraints

**maximum length**: the maximum number of characters for this string is: `64`

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:

```text
^[^.]*$
```

[try pattern](https://regexr.com/?expression=%5E%5B%5E.%5D*%24)

### columnDataType

Type for capturing a column in a table

`columnDataType`

* is required
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-columndatatype.md)

#### columnDataType Type

`string`

#### columnDataType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"NUMBER"` |  |
| `"TINYINT"` |  |
| `"SMALLINT"` |  |
| `"INT"` |  |
| `"BIGINT"` |  |
| `"FLOAT"` |  |
| `"DOUBLE"` |  |
| `"DECIMAL"` |  |
| `"NUMERIC"` |  |
| `"TIMESTAMP"` |  |
| `"TIME"` |  |
| `"DATE"` |  |
| `"DATETIME"` |  |
| `"INTERVAL"` |  |
| `"STRING"` |  |
| `"MEDIUMTEXT"` |  |
| `"TEXT"` |  |
| `"CHAR"` |  |
| `"VARCHAR"` |  |
| `"BOOLEAN"` |  |
| `"BINARY"` |  |
| `"VARBINARY"` |  |
| `"ARRAY"` |  |
| `"BLOB"` |  |
| `"LONGBLOB"` |  |
| `"MEDIUMBLOB"` |  |
| `"MAP"` |  |
| `"STRUCT"` |  |
| `"UNION"` |  |
| `"SET"` |  |
| `"GEOGRAPHY"` |  |
| `"ENUM"` |  |
| `"JSON"` |  |

### description

Description of the column

`description`

* is optional
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-column-properties-description.md)

#### description Type

`string`

### fullyQualifiedName

Fully qualified name of the column that includes serviceName.databaseName.tableName.columnName

`fullyQualifiedName`

* is optional
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-fullyqualifiedcolumnname.md)

#### fullyQualifiedName Type

`string`

#### fullyQualifiedName Constraints

**maximum length**: the maximum number of characters for this string is: `256`

**minimum length**: the minimum number of characters for this string is: `1`

### tags

Tags associated with the column

`tags`

* is optional
* Type: `object[]` \([Details](../../types/common/common-definitions-taglabel.md)\)
* cannot be null
* defined in: [Table entity](table-definitions-column-properties-tags.md)

#### tags Type

`object[]` \([Details](../../types/common/common-definitions-taglabel.md)\)

### columnConstraint

Column constraint

`columnConstraint`

* is optional
* Type: `string`
* cannot be null
* defined in: [Table entity](table-definitions-columnconstraint.md)

#### columnConstraint Type

`string`

#### columnConstraint Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value | Explanation |
| :--- | :--- |
| `"NULL"` |  |
| `"NOT_NULL"` |  |
| `"UNIQUE"` |  |
| `"PRIMARY_KEY"` |  |

#### columnConstraint Default Value

The default value is:

```javascript
"NULL"
```

### ordinalPosition

Ordinal position of the column

`ordinalPosition`

* is optional
* Type: `integer`
* cannot be null
* defined in: [Table entity](table-definitions-column-properties-ordinalposition.md)

#### ordinalPosition Type

`integer`

