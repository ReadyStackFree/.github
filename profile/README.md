# ReadyStack

ReadyStack packages open-source software as signed container images, each built with the network off from pinned
inputs, and publishes what you need to check them: the recipe each image was built from, its software bill of materials
(SBOM), its build provenance and its daily scan results.

- **Products and releases:** https://readystack.dev/products.html
- **Recipes** (the pinned inputs and build files of each release): `https://readystack.dev/products/<product>/recipe`
- **Images:** https://hub.docker.com/u/readystack
- **Report a problem or ask for a product:** https://github.com/ReadyStackFree/readystack/issues
- **Known defects, per release:** https://readystack.dev/defects.html
- **What is being built now:** https://readystack.dev/queue
- **Release signing key (cosign):** https://readystack.dev/keys/cosign.pub
- **Security reports:** see [SECURITY.md](https://github.com/ReadyStackFree/.github/blob/main/SECURITY.md)

## Public repositories here

- [readystack](https://github.com/ReadyStackFree/readystack): the public issue tracker for every ReadyStack image and
  for the website.
- [rebuild-bundle-spec](https://github.com/ReadyStackFree/rebuild-bundle-spec): the ReadyStack Rebuild Bundle
  specification (draft) and a reference verifier, for rebuilding a published image offline and checking that it is
  bit-for-bit identical.
- [consul](https://github.com/ReadyStackFree/consul): Consul v1.16.4, the last MPL-2.0 release, with security fixes
  we backported (see its READYSTACK.md).
- [grpc-go](https://github.com/ReadyStackFree/grpc-go), [opentelemetry-go](https://github.com/ReadyStackFree/opentelemetry-go),
  [go-archive](https://github.com/ReadyStackFree/go-archive): forks carrying security fixes our builds use when a
  product depends on a version upstream has not fixed. [cli](https://github.com/ReadyStackFree/cli) and
  [compose](https://github.com/ReadyStackFree/compose) are forks of docker/cli and docker/compose kept for the same
  purpose.

ReadyStack is soon to be a nonprofit. If you would like to take part, email contact@readystack.dev.
