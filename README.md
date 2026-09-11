# OSS CI isolation lab

Synthetic external fork PR used to compare GitHub Actions secret withholding with Harness conditional execution and chained pipelines.

This branch intentionally changes the Harness YAML and includes a bounded credential-presence probe. Only the upstream pipeline definitions should run.

This revision also validates commit status reporting from a separate trusted runner.
