# Use Case: MDBook
$slides-only$
- Static Site Generator 
- Candidate: Plugin System
    - Uses Pipes to pass JSON between processes
    - Executes plugin twice
        - Once with argument for renderer
        - Once with JSON of Book
$slides-only-end$

$notes$
- MdBook
  - Static Site Gen
  - Has Plugins
  - Uses STDIO
    - STDIO is not always reliable
    - Anti-virus spam example
  - Called twice
    - once for renderer
    - once with JSON
$notes-end$