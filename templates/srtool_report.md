# Srtool report for {{ pkg }}

This report has been generated with **{{gen}}** at {{ tmsp }}. You can find more about `srtool` at https://gitlab,com/chevdor/srtool.

This version uses **{{rustc}}**.

The source comes from **{{src}}**:
- version: {{ version }}
- commit: {{ commit }}

Here are some properties of the generated runtime:
- size: {{ size | int() | filesizeformat }} ({{ size }} bytes)
- proposal hash: {{prop}}
- ipfs: {{ipfs}} - [{{ipfs}}](https://ipfs.io/ipfs/{{ipfs}})
- sha256: {{ sha256}}

The WASM can be found at: {{wasm}}
