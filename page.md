## Subsets of JSON

+ ### Son

    GitHub: [https://github.com/seagreen/Son](https://github.com/seagreen/Son)

    Disclaimer: my project.

+ ### JSON Canonical Form

    IETF draft: [draft-staykov-hu-json-canonical-form-00](https://tools.ietf.org/html/draft-staykov-hu-json-canonical-form-00)

+ ### Canonical JSON (One Laptop Per Child)

    Description: [http://wiki.laptop.org/go/Canonical_JSON](http://wiki.laptop.org/go/Canonical_JSON)

    Notes: not actually a subset of JSON. Canonical JSON is specified in bytes while JSON is specified in code points. Canonical JSON allows any possible byte to appear as the member of a string (with some escaping rules around ASCII `"` and ASCII `\`).

    JSON forbids code points below %x20 and above %x10FFFF, which means that %x19 is valid Canonical JSON but invalid JSON. The only exception would be if you interpreted it as JSON in some form of exotic encoding where the byte %x19 maps to a valid code point (ruling out UTF-16, UTF-32, etc.) but doesn't map to the code point %x19 (ruling out ASCII and UTF-8). This seems farfetched.

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
