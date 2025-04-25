# SMAPI JSON

A Rust library for serializing [JSON5](https://json5.org/) and deserializing SMAPI JSON.

SMAPI JSON allows even more than JSON5. Specifically,

- String literals can have control characters (including newlines) directly in them.
- Multiple commas in a row are treated as a single comma.
- Integer literals can be keys in objects.
- Files can be completely empty.
