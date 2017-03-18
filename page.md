## Subsets of JSON

+ ### Son

    GitHub: [https://github.com/seagreen/Son](https://github.com/seagreen/Son)

    Disclaimer: my project.

+ ### JSON Canonical Form

    IETF draft: [draft-staykov-hu-json-canonical-form-00](https://tools.ietf.org/html/draft-staykov-hu-json-canonical-form-00)

    Note: the mapping from JSON Canonical Form to bytes is ambiguous. It doesn't specify which characters should be escaped or which escape sequences to use.

+ ### Canonical JSON (One Laptop Per Child)

    Description: [http://wiki.laptop.org/go/Canonical_JSON](http://wiki.laptop.org/go/Canonical_JSON)

    Note: not actually a subset of JSON. JSON forbids code points below %x20, but Canonical JSON (which is actually specified in bytes, not code points) allows all bytes to appear in strings.

+ ### I-JSON

    IETF: [rfc7493](https://tools.ietf.org/html/rfc7493)

## Supersets of JSON

+ ### JSON5

    Extension: `json5`

    Website: [http://json5.org/](http://json5.org/)

+ ### Hjson

    Website: [https://hjson.org/](https://hjson.org/)

+ ### HOCON (Human-Optimized Config Object Notation)

    Description: [https://github.com/typesafehub/config/blob/master/HOCON.md](https://github.com/typesafehub/config/blob/master/HOCON.md)

## Transpiles to JSON

+ ### Markdown Syntax for Object Notation (MSON)

    GitHub: [https://github.com/apiaryio/mson](https://github.com/apiaryio/mson)
