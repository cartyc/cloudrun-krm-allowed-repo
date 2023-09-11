# cloud-run-policies

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] cloud-run-policies`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree cloud-run-policies`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init cloud-run-policies
kpt live apply cloud-run-policies --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
