# Attachments to the document Schema

```txt
open-attestation/3.0#/properties/attachments/items
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [tradetrust.schema.json\*](../out/tradetrust.schema.json "open original schema") |

## items Type

`object` ([Attachments to the document](tradetrust-properties-attachments-attachments-to-the-document.md))

# Attachments to the document Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                  |
| :-------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [filename](#filename) | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-filename.md "open-attestation/3.0#/properties/attachments/items/properties/filename") |
| [type](#type)         | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-type.md "open-attestation/3.0#/properties/attachments/items/properties/type")         |
| [mimeType](#mimeType) | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-mimetype.md "open-attestation/3.0#/properties/attachments/items/properties/mimeType") |
| [data](#data)         | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-data.md "open-attestation/3.0#/properties/attachments/items/properties/data")         |

## filename

Name of attachment, with appropriate extensions


`filename`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-filename.md "open-attestation/3.0#/properties/attachments/items/properties/filename")

### filename Type

`string`

## type

A valid evidence type as explained by <https://www.w3.org/TR/vc-data-model/#types>


`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-type.md "open-attestation/3.0#/properties/attachments/items/properties/type")

### type Type

`string`

## mimeType

Mime-type of attachment


`mimeType`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-mimetype.md "open-attestation/3.0#/properties/attachments/items/properties/mimeType")

### mimeType Type

`string`

### mimeType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value               | Explanation |
| :------------------ | ----------- |
| `"application/pdf"` |             |
| `"image/png"`       |             |
| `"image/jpeg"`      |             |

## data

Base64 encoding of attachment


`data`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-attachments-attachments-to-the-document-properties-data.md "open-attestation/3.0#/properties/attachments/items/properties/data")

### data Type

`string`
