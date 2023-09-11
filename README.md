# cloud-run-policies

## Description
This is an example repository demonstrating the use of the Kpt gatekeeper function to prevent the deployment of a KCC based Cloud Run instance from deploying with a disallowed container.

This is a modification of the [k8s-allowed-repo](https://github.com/open-policy-agent/gatekeeper-library/tree/master/library/general/allowedrepos) policy.

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] cloud-run-policies`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree cloud-run-policies`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt fn render
```
