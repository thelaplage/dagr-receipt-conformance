# Legacy compatibility identifiers

DAGR Receipt Conformance is the active product and repository name. The former
GARP name is retired from product vocabulary, documentation entry points,
examples, badges, ecosystem manifests, and cross-repository links.

Some GARP-spelled values remain intentionally unchanged because they are part
of released wire formats, digest-pinned artifacts, or historical provenance.
They are **legacy compatibility identifiers**, not active product branding.

Preserve byte-for-byte:

- The `extensions.garp.*` wire namespace, including
  `extensions.garp.body` and its receipt fields.
- Released schema identifiers, including
  `https://garp.doctrine/schemas/srs/srs-envelope.schema.json`.
- Published schema, fixture, manifest, validator, and expected-output bytes
  whose digests or provenance records are already pinned.
- Historical repository, pull-request, producer, and commit references when
  they identify the origin of already-published evidence.
- Existing validator error codes and fixture names when changing them would
  break compatibility or expected-output checks.

Use DAGR for all new repository names, prose, examples, links, and identifiers.
Do not mint a parallel `extensions.dagr.*` namespace as part of this rename.
Any future wire-format migration requires its own versioned specification,
fixtures, compatibility policy, and conformance release.
