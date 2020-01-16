# Rendering Template Info Schema

```txt
open-attestation/3.0#/properties/template
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [tradetrust.schema.json\*](../out/tradetrust.schema.json "open original schema") |

## template Type

`object` ([Rendering Template Info](tradetrust-properties-rendering-template-info.md))

# Rendering Template Info Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                 |
| :------------ | -------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name) | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-rendering-template-info-properties-name.md "open-attestation/3.0#/properties/template/properties/name") |
| [type](#type) | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-rendering-template-info-properties-type.md "open-attestation/3.0#/properties/template/properties/type") |
| [url](#url)   | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-rendering-template-info-properties-url.md "open-attestation/3.0#/properties/template/properties/url")   |

## name

Template name to be use by template renderer to determine the template to use


`name`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-rendering-template-info-properties-name.md "open-attestation/3.0#/properties/template/properties/name")

### name Type

`string`

## type

Type of renderer template


`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-rendering-template-info-properties-type.md "open-attestation/3.0#/properties/template/properties/type")

### type Type

`string`

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                 | Explanation |
| :-------------------- | ----------- |
| `"EMBEDDED_RENDERER"` |             |

## url

URL of a decentralised renderer to render this document


`url`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-rendering-template-info-properties-url.md "open-attestation/3.0#/properties/template/properties/url")

### url Type

`string`

### url Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(https?)://
```

[try pattern](https://regexr.com/?expression=%5E(https%3F)%3A%2F%2F "try regular expression with regexr.com")
