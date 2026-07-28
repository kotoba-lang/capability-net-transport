# capability-net-transport

Atomic authority package for `net/transport`.

- imports: `#{:transport-write :transport-close :transport-read}`
- effects: `#{:data-egress :network-read :network-write}`
- default policy: `:approval-required`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
