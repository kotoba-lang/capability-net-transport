# capability-net-transport

Atomic authority package for `net/transport`.

- imports: `#{:transport-write :transport-close :transport-read}`
- effects: `#{:data-egress :network-read :network-write}`
- default policy: `:approval-required`
- semantic definition CID: `bafyreicau5taerbqprf56lozef43vgiqygffa6muiuniati2ejmrkrpwzm`
- hash contract CID: `bafkreiflhj3fslsbh7okdas2fzlhmogai64x6p3lkla6gtr7berbp7ftvi`
- provider status: `contract-only`

The repository name is a discovery alias. The semantic definition CID
is the immutable import identity. Importing it does not grant runtime
authority: Tamaki must request it explicitly and Kototama must admit
the sealed envelope.

```sh
clojure -M:test
```
