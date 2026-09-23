# vercel-prebuilt

Public reusable workflow that builds Vercel projects on 1REALTOUR BUILD-RUNNER.

It contains no credentials. A caller repository must be on the allowlist inside
the workflow. GitHub OIDC is exchanged for a short-lived Infisical identity
bound to this workflow file on `main`. Forks are refused before that exchange.
