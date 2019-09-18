# Possible Solution
$slides-only$
- MDBook could host a WASM Runtime
  - This could be used to execute plugins
- Wasm API
    - Expose 2 function
        - 1st Takes renderer string returns bool
        - 2nd Takes Book returns modified Book
- Helpers?
$slides-only-end$
$notes$
Solution
--------
- MDBook could host a WASM Runtime
  - use this to execute plugins
- MDBook = Rust
  - Could develop plugins in Rust
- API would expose 2 function
  - these replicate the CLI interactions
    - renderer -> bool
    - book -> modified book
- Helpers?
  - Wasm data transfer can be a pain
    - Helpers to perform memory access
    - and serialization/deserialization
$notes-end$