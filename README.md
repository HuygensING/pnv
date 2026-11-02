# Person Name Vocabulary (PNV)

An RDF vocabulary and data model for persons' names.

- Persistent URI: <https://w3id.org/pnv>
- Documentation: <https://w3id.org/pnv> (in a browser) or <https://huygensing.github.io/pnv/doc/>

## Files

| Format | File |
| --- | --- |
| Turtle | [`pnv.ttl`](pnv.ttl) |
| RDF/XML | [`pnv.rdf`](pnv.rdf) |
| JSON-LD | [`pnv.jsonld`](pnv.jsonld) |
| N-Triples | [`pnv.nt`](pnv.nt) |
| OWL/XML | [`pnv.owl`](pnv.owl) |

The HTML documentation (generated with [Widoco](https://github.com/dgarijo/Widoco)) is in [`doc/`](doc/), and a [WebVOWL](http://vowl.visualdataweb.org/) visualization is in [`webvowl/`](webvowl/).

## Hosting

This repository is published with GitHub Pages at <https://huygensing.github.io/pnv/>. Requests for `https://w3id.org/pnv` are redirected here with content negotiation; the rules are kept in [`w3id/.htaccess`](w3id/.htaccess) and live in the [w3id.org repository](https://github.com/perma-id/w3id.org/tree/master/ids/pnv).

PNV uses hash URIs (e.g. `https://w3id.org/pnv#PersonName`), so individual classes and properties need no separate redirects: browsers land on the matching anchor in the documentation, RDF clients get the whole vocabulary.

When changing the vocabulary, keep all serializations in sync.

## License

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
