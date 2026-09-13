# actions-default-token-statuses

A two-arm differential: can a workflow that declares no `permissions:` block use the default
`GITHUB_TOKEN` to create a commit status?

Arm A runs with the repository default set to "Read repository contents and packages permissions".
Arm B runs with it set to "Read and write permissions". The workflow file is identical in both arms.
