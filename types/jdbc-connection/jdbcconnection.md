# jdbcconnection

## JDBC connection Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/jdbcConnection.json
```

JDBC connection information used for connecting to a database system

> JDBC connection information

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | Yes | Unknown status | No | Forbidden | Allowed | none | [jdbcConnection.json](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/jdbcConnection.json) |

### JDBC connection Type

`object` \([JDBC connection](jdbcconnection.md)\)

## JDBC connection Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [driverClass](jdbcconnection.md#driverclass) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-driverclass.md) |
| [connectionUrl](jdbcconnection.md#connectionurl) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-connectionurl.md) |
| [userName](jdbcconnection.md#username) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-username.md) |
| [password](jdbcconnection.md#password) | `string` | Required | cannot be null | [JDBC connection](jdbcconnection-properties-password.md) |

### driverClass

> Type used for JDBC driver class

`driverClass`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](jdbcconnection-properties-driverclass.md)

#### driverClass Type

`string`

### connectionUrl

> Type used for JDBC connection URL

`connectionUrl`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](jdbcconnection-properties-connectionurl.md)

#### connectionUrl Type

`string`

#### connectionUrl Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### userName

Login user name

`userName`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](jdbcconnection-properties-username.md)

#### userName Type

`string`

### password

Login password

`password`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](jdbcconnection-properties-password.md)

#### password Type

`string`

## JDBC connection Definitions

### Definitions group driverClass

Reference this group by using

```javascript
{"$ref":"https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/jdbcConnection.json#/definitions/driverClass"}
```

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |


### Definitions group connectionUrl

Reference this group by using

```javascript
{"$ref":"https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/jdbcConnection.json#/definitions/connectionUrl"}
```

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |


### Definitions group jdbcInfo

Reference this group by using

```javascript
{"$ref":"https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/jdbcConnection.json#/definitions/jdbcInfo"}
```

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [driverClass](jdbcconnection.md#driverclass-1) | `string` | Required | cannot be null | [JDBC connection](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/Jdbc-Connection/jdbcconnection-definitions-jdbcinfo-properties-driverclass.md) |
| [connectionUrl](jdbcconnection.md#connectionurl-1) | `string` | Required | cannot be null | [JDBC connection](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/Jdbc-Connection/jdbcconnection-definitions-jdbcinfo-properties-connectionurl.md) |

#### driverClass

> Type used for JDBC driver class

`driverClass`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/Jdbc-Connection/jdbcconnection-definitions-jdbcinfo-properties-driverclass.md)

**driverClass Type**

`string`

**driverClass Default Value**

The default value is:

```javascript
"com.amazon.redshift.jdbc42.Driver"
```

#### connectionUrl

> Type used for JDBC connection URL

`connectionUrl`

* is required
* Type: `string`
* cannot be null
* defined in: [JDBC connection](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/Jdbc-Connection/jdbcconnection-definitions-jdbcinfo-properties-connectionurl.md)

**connectionUrl Type**

`string`

**connectionUrl Constraints**

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

