# ext-splitus

Public contract repository for the Sneat Splitus extension.

`frontend/` owns and publishes `@sneat/extension-splitus-contract`. It contains
only stable models, service interfaces, and injection tokens. The private
`debtus` repository owns all runtime providers, UI, applications, and
deployment configuration for Splitus.

## Publish

Pushing to `main` builds and publishes the package through the shared
`sneat-co/cicd` workflow.
