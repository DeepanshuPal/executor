---
"@executor-js/sdk": patch
---

A client_credentials sign-in no longer fails when the token response leaves out `token_type`, as Shopify's Admin API does. The grant now defaults to Bearer and reads a comma-separated `scope` as a list.
