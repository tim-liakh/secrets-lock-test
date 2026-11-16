# timothy-liakh-secrets-lock-test

Staging test fixture for K9CODESEC-9675 (generic secrets cold-start lock).

`fixture/` is a copy of a subset of `types/` from [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped), MIT licensed (see `fixture/LICENSE`).
It only exists so the generic secrets scan has enough files to exercise multiple cold-start passes in staging.
