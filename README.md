# Go (Awesome KB)

An [OpenShelf](https://github.com/OpenNorms/openshelf) 1.7 knowledge base
ingested from [avelino/awesome-go](https://github.com/avelino/awesome-go), part of the
[Awesome KB](https://github.com/hexsecs/awesome-kb) network.

**[Browse the knowledge base](index.md).** All entries start at stub depth.
This is an initial inventory import, not independent verification of projects.
The list remains canon. Original resource URLs, descriptions, categories and
source revision are retained. Linked lists are not recursively ingested.

## Reproduce and validate

```sh
python3 tools/ingest.py --date 2026-11-04
python3 tools/check.py
openshelf lint .
```

The immutable source capture is under raw/2026-11-04; see capture.json for
provenance and AGENTS.md for maintenance. CI checks completeness, links,
checksums, identity, idempotency, authored-depth preservation and OpenShelf lint.

## License and attribution

Content follows upstream's **MIT** license, reproduced in [LICENSE](LICENSE).
Original list content is attributed to [avelino/awesome-go](https://github.com/avelino/awesome-go);
this KB transforms each list entry into an OpenShelf stub and generated indexes.
Linked projects retain their own licenses. No endorsement is implied.
Source revision: [5e201a5e2340](https://github.com/avelino/awesome-go/tree/5e201a5e2340964477bbf5dc1babf83577606f92).
