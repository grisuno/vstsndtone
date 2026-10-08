# root

*Community 0 | 1 files | cohesion 1.00*

## Definition

This community groups 1 file(s) rooted at `root` with dominant language cpp (cohesion 1.00). Central symbols: `ToneGenerator`, `canDo`, `generateTone`, `processReplacing`. Core file: `main.cpp` (4 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `main.cpp` | cpp | utility | 4 | no |

## Key Symbols

- `ToneGenerator` (class, `main.cpp:5`)
- `processReplacing` (function, `main.cpp:21`) `virtual void processReplacing(float** inputs, float** outputs, VstInt32 sampleFr`
- `generateTone` (function, `main.cpp:34`) `float generateTone()`
- `canDo` (function, `main.cpp:40`) `virtual VstInt32 canDo(char* text)`

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 0
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 1 file(s) lack file-level docs (e.g. `main.cpp`)? What purpose do they serve?
- What would break if the most connected file in root changed?
- Should root be split, given cohesion 1.00?

## Sources

- `main.cpp`
