# Open Attestation Schema v3 Schema

```txt
open-attestation/3.0
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                     |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [tradetrust.schema.json](../out/tradetrust.schema.json "open original schema") |

## Open Attestation Schema v3 Type

`object` ([Open Attestation Schema v3](tradetrust.md))

# Open Attestation Schema v3 Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                        |
| :-------------------------- | -------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| [@context](#@context)       | `array`  | Optional | cannot be null | [Open Attestation Schema v3](tradetrust-properties-context.md "open-attestation/3.0#/properties/@context")                        |
| [id](#id)                   | `string` | Optional | cannot be null | [Open Attestation Schema v3](tradetrust-properties-id.md "open-attestation/3.0#/properties/id")                                   |
| [reference](#reference)     | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-reference.md "open-attestation/3.0#/properties/reference")                     |
| [name](#name)               | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-name.md "open-attestation/3.0#/properties/name")                               |
| [type](#type)               | `array`  | Optional | cannot be null | [Open Attestation Schema v3](tradetrust-properties-verifiable-credential-types.md "open-attestation/3.0#/properties/type")        |
| [validFrom](#validFrom)     | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-validfrom.md "open-attestation/3.0#/properties/validFrom")                     |
| [validUntil](#validUntil)   | `string` | Optional | cannot be null | [Open Attestation Schema v3](tradetrust-properties-validuntil.md "open-attestation/3.0#/properties/validUntil")                   |
| [issuer](#issuer)           | `object` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-issuer-info.md "open-attestation/3.0#/properties/issuer")                      |
| [template](#template)       | `object` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-rendering-template-info.md "open-attestation/3.0#/properties/template")        |
| [proof](#proof)             | `object` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-document-status-proof.md "open-attestation/3.0#/properties/proof")             |
| [recipient](#recipient)     | `object` | Optional | cannot be null | [Open Attestation Schema v3](tradetrust-properties-recipientsubject-of-document.md "open-attestation/3.0#/properties/recipient")  |
| [attachments](#attachments) | `array`  | Optional | cannot be null | [Open Attestation Schema v3](tradetrust-properties-attachments-to-the-document.md "open-attestation/3.0#/properties/attachments") |
| Additional Properties       | Any      | Optional | can be null    |                                                                                                                                   |

## @context

List of URI to determine the terminology used in the verifiable credential as explained by <https://www.w3.org/TR/vc-data-model/#contexts>


`@context`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-context.md "open-attestation/3.0#/properties/@context")

### @context Type

`string[]`

## id

URI to the subject of the credential as explained by <https://www.w3.org/TR/vc-data-model/#credential-subject>


`id`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-id.md "open-attestation/3.0#/properties/id")

### id Type

`string`

### id Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc4291 "check the specification")

## reference

Internal reference, usually serial number, of this document


`reference`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-reference.md "open-attestation/3.0#/properties/reference")

### reference Type

`string`

## name

Human readable name of the credential


`name`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-name.md "open-attestation/3.0#/properties/name")

### name Type

`string`

## type

Specific verifiable credential type as explained by <https://www.w3.org/TR/vc-data-model/#types>


`type`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-verifiable-credential-types.md "open-attestation/3.0#/properties/type")

### type Type

`string[]`

## validFrom

Date and time when a credential becomes valid.


`validFrom`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-validfrom.md "open-attestation/3.0#/properties/validFrom")

### validFrom Type

`string`

### validFrom Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## validUntil

Date and time when a credential becomes valid.


`validUntil`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-validuntil.md "open-attestation/3.0#/properties/validUntil")

### validUntil Type

`string`

### validUntil Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## issuer




`issuer`

-   is required
-   Type: `object` ([Issuer Info](tradetrust-properties-issuer-info.md))
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-issuer-info.md "open-attestation/3.0#/properties/issuer")

### issuer Type

`object` ([Issuer Info](tradetrust-properties-issuer-info.md))

## template




`template`

-   is required
-   Type: `object` ([Rendering Template Info](tradetrust-properties-rendering-template-info.md))
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-rendering-template-info.md "open-attestation/3.0#/properties/template")

### template Type

`object` ([Rendering Template Info](tradetrust-properties-rendering-template-info.md))

## proof




`proof`

-   is required
-   Type: `object` ([Document Status Proof](tradetrust-properties-document-status-proof.md))
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-document-status-proof.md "open-attestation/3.0#/properties/proof")

### proof Type

`object` ([Document Status Proof](tradetrust-properties-document-status-proof.md))

## recipient




`recipient`

-   is optional
-   Type: `object` ([Recipient/subject of Document](tradetrust-properties-recipientsubject-of-document.md))
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-recipientsubject-of-document.md "open-attestation/3.0#/properties/recipient")

### recipient Type

`object` ([Recipient/subject of Document](tradetrust-properties-recipientsubject-of-document.md))

## attachments




`attachments`

-   is optional
-   Type: `object[]` ([Attached file](tradetrust-properties-attachments-to-the-document-attached-file.md))
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-attachments-to-the-document.md "open-attestation/3.0#/properties/attachments")

### attachments Type

`object[]` ([Attached file](tradetrust-properties-attachments-to-the-document-attached-file.md))

## Additional Properties

Additional properties are allowed and do not have to follow a specific schema
