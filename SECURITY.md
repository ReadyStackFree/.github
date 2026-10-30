# Reporting a security problem

Please do not open a public issue for a vulnerability.

- **Privately on GitHub:** use "Report a vulnerability" on the
  [issue tracker's Security tab](https://github.com/ReadyStackFree/readystack/security/advisories/new).
- **By email:** support@readystack.dev, as listed in https://readystack.dev/.well-known/security.txt

Say which image and release tag (or digest) is affected, and how to reproduce the problem. Current ReadyStack releases
are signed; you can check an image with
`cosign verify --key https://readystack.dev/keys/cosign.pub readystack/<product>:<tag>`.

Known, published defects of each release are listed at https://readystack.dev/defects.html.
