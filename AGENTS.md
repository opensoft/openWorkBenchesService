Read AGENTS-shape.md first — the rules of this repository's shape.

This is the assembly root of **openWorkBenchesService** (`openworkbenchesservice`): the repository an
engineer clones. It holds `project.yaml`, the pins and the gate, and it mounts
the two legs.

| role | repository | path |
|---|---|---|
| assembly | `opensoft/openWorkBenchesService` | `.` |
| spec | `opensoft/openWorkBenchesService-spec` | `spec/` |
| code | `opensoft/openWorkBenchesService-code` | `code/` |

Everything below this line is openWorkBenchesService's own. The shape wrote the block above
once and does not pin this file, so how this project is built, tested, reviewed
and released belongs here and nothing upstream will overwrite it.
