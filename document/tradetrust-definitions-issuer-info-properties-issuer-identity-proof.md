# Issuer Identity Proof Schema

```txt
open-attestation/3.0#/definitions/issuer/properties/identityProof
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [tradetrust.schema.json\*](../out/tradetrust.schema.json "open original schema") |

## identityProof Type

`object` ([Issuer Identity Proof](tradetrust-definitions-issuer-info-properties-issuer-identity-proof.md))

# Issuer Identity Proof Properties

| Property              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                       |
| :-------------------- | -------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)         | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-definitions-issuer-info-properties-issuer-identity-proof-properties-type.md "open-attestation/3.0#/definitions/issuer/properties/identityProof/properties/type")         |
| [location](#location) | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-definitions-issuer-info-properties-issuer-identity-proof-properties-location.md "open-attestation/3.0#/definitions/issuer/properties/identityProof/properties/location") |

## type




`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-definitions-issuer-info-properties-issuer-identity-proof-properties-type.md "open-attestation/3.0#/definitions/issuer/properties/identityProof/properties/type")

### type Type

`string`

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | ----------- |
| `"DNS-TXT"` |             |

## location

Url of the website referencing to document store


`location`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-definitions-issuer-info-properties-issuer-identity-proof-properties-location.md "open-attestation/3.0#/definitions/issuer/properties/identityProof/properties/location")

### location Type

`string`
