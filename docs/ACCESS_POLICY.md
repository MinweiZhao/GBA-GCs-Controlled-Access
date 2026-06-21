# Controlled Access Policy

## Who May Request Access

Access may be requested by academic or non-profit researchers with an institutional affiliation, a clearly scoped non-commercial research purpose, and a data security plan.

Requests from commercial entities, law enforcement, surveillance vendors, real-estate targeting systems, advertising systems, or projects involving individual- or household-level profiling are not eligible.

## Review Criteria

Requests are reviewed against:

- research purpose and public-interest justification
- need for controlled fields rather than public anonymized data
- data minimization plan
- institutional affiliation and accountable contact
- storage and deletion plan
- publication plan
- risk of re-identification, targeting, or surveillance misuse
- compatibility with third-party provider terms

## Access Levels

- **Public**: anonymized labels and coarse bins in the public repository.
- **Controlled metadata**: crosswalks, provider-derived metadata, AOI geometries, and checksums under DUA.
- **Controlled imagery**: image chips only when requester has appropriate legal/ethical permission and storage controls.

## Request Workflow

1. Complete `forms/ACCESS_REQUEST_FORM.md`.
2. Send the form, institutional email, and signed DUA to the maintainers.
3. Maintainers review purpose, risk, and requested components.
4. If approved, archives are distributed through access-controlled storage, not public GitHub.
5. Requester verifies received files using `metadata/checksums_sha256.txt`.
6. Requester follows all storage, reporting, and deletion requirements.

