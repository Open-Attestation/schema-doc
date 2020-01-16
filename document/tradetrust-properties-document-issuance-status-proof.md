# Document Issuance Status Proof Schema

```txt
open-attestation/3.0#/properties/proof
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [tradetrust.schema.json\*](../out/tradetrust.schema.json "open original schema") |

## proof Type

`object` ([Document Issuance Status Proof](tradetrust-properties-document-issuance-status-proof.md))

# Document Issuance Status Proof Properties

| Property          | Type     | Required | Nullable       | Defined by                                                                                                                                                         |
| :---------------- | -------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)     | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-document-issuance-status-proof-properties-type.md "open-attestation/3.0#/properties/proof/properties/type")     |
| [method](#method) | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-document-issuance-status-proof-properties-method.md "open-attestation/3.0#/properties/proof/properties/method") |
| [value](#value)   | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-properties-document-issuance-status-proof-properties-value.md "open-attestation/3.0#/properties/proof/properties/value")   |

## type

Proof method name as explained by <https://www.w3.org/TR/vc-data-model/#types>


`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-document-issuance-status-proof-properties-type.md "open-attestation/3.0#/properties/proof/properties/type")

### type Type

`string`

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                            | Explanation |
| :------------------------------- | ----------- |
| `"OpenAttestationSignature2018"` |             |

## method

Proof open attestation method


`method`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-document-issuance-status-proof-properties-method.md "open-attestation/3.0#/properties/proof/properties/method")

### method Type

`string`

### method Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | ----------- |
| `"TOKEN_REGISTRY"` |             |
| `"DOCUMENT_STORE"` |             |

## value

Proof value for issuer(s)


`value`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-properties-document-issuance-status-proof-properties-value.md "open-attestation/3.0#/properties/proof/properties/value")

### value Type

`string`
