# collectiondescriptor-definitions-collectioninfo

## Untitled object in Schema for collection descriptor Schema

```text
https://github.com/StreamlineData/catalog/blob/master/catalog-rest-service/src/main/resources/json/schema/type/collectionDescriptor.json#/properties/collection
```

Collection Info

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Can be instantiated | No | Unknown status | No | Forbidden | Allowed | none | [collectionDescriptor.json\*](https://github.com/parthp2107/jsonTesting/tree/982c19ce17ac8d846e924786a3bf1598f2ce11b7/Types/out/type/collectionDescriptor.json) |

### collection Type

`object` \([Details](collectiondescriptor-definitions-collectioninfo.md)\)

## collection Properties

| Property | Type | Required | Nullable | Defined by |
| :--- | :--- | :--- | :--- | :--- |
| [name](collectiondescriptor-definitions-collectioninfo.md#name) | `string` | Optional | cannot be null | [Schema for collection descriptor](collectiondescriptor-definitions-collectioninfo-properties-name.md) |
| [documentation](collectiondescriptor-definitions-collectioninfo.md#documentation) | `string` | Optional | cannot be null | [Schema for collection descriptor](collectiondescriptor-definitions-collectioninfo-properties-documentation.md) |
| [href](collectiondescriptor-definitions-collectioninfo.md#href) | `string` | Optional | cannot be null | [Schema for collection descriptor](collectiondescriptor-definitions-collectioninfo-properties-href.md) |
| [images](collectiondescriptor-definitions-collectioninfo.md#images) | `object` | Optional | cannot be null | [Schema for collection descriptor](../common/common-definitions-imagelist.md) |

### name

Unique name that identifies a collection

`name`

* is optional
* Type: `string`
* cannot be null
* defined in: [Schema for collection descriptor](collectiondescriptor-definitions-collectioninfo-properties-name.md)

#### name Type

`string`

### documentation

Description of collection

`documentation`

* is optional
* Type: `string`
* cannot be null
* defined in: [Schema for collection descriptor](collectiondescriptor-definitions-collectioninfo-properties-documentation.md)

#### documentation Type

`string`

### href

URL of the API endpoint where given collections are available

`href`

* is optional
* Type: `string`
* cannot be null
* defined in: [Schema for collection descriptor](collectiondescriptor-definitions-collectioninfo-properties-href.md)

#### href Type

`string`

#### href Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986)

### images

> Links to list of images of varying resolutions/sizes

`images`

* is optional
* Type: `object` \([Details](../common/common-definitions-imagelist.md)\)
* cannot be null
* defined in: [Schema for collection descriptor](../common/common-definitions-imagelist.md)

#### images Type

`object` \([Details](../common/common-definitions-imagelist.md)\)

