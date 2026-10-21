# Lab reproduction, security research

Not a product. Reproduces the caller-to-sink composition reported to Elastic so the
injection can be demonstrated on a real GitHub-hosted runner without touching any
Elastic repository.

The "Select files to lint" step and the sink step are copied verbatim; see the
header comments in `.github/workflows/vale-lint.yml`.
