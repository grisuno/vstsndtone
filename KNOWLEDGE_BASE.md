# Polyglot Codebase Knowledge Graph

> Generated offline by **readmenator**. Supports C, C++, Python, Go, Rust, JS/TS, Java, C#, Shell, PHP, Dart, GDScript, Nim, ASM.
> No LLMs. No tokens. Pure static analysis.

**Total Files Parsed:** 1 | **Total Symbols Extracted:** 4 | **Total Imports:** 3

## Structural Knowledge Map
```mermaid
graph TD
    classDef mod fill:#1e1e1e,stroke:#ff6666,stroke-width:2px,color:#fff;
    classDef cls fill:#2d2d2d,stroke:#4ec9b0,stroke-width:2px,color:#fff;
    classDef fn fill:#333,stroke:#dcdcaa,stroke-width:1px,color:#dcdcaa;
    classDef ext fill:#111,stroke:#666,stroke-dasharray: 5 5,color:#aaa;
    main_cpp["main.cpp (cpp)"]
    class main_cpp mod;
    main_cpp_ToneGenerator["ToneGenerator"]
    class main_cpp_ToneGenerator cls;
    main_cpp --> main_cpp_ToneGenerator
    main_cpp_processReplacing["processReplacing"]
    class main_cpp_processReplacing fn;
    main_cpp --> main_cpp_processReplacing
    main_cpp_generateTone["generateTone"]
    class main_cpp_generateTone fn;
    main_cpp --> main_cpp_generateTone
    main_cpp_canDo["canDo"]
    class main_cpp_canDo fn;
    main_cpp --> main_cpp_canDo
    ext_cmath["cmath"]
    class ext_cmath ext;
    main_cpp -.->|imports| ext_cmath
    ext_array["array"]
    class ext_array ext;
    main_cpp -.->|imports| ext_array
    ext_public_sdk_source_vst2_x_audioeffectx_h["audioeffectx.h"]
    class ext_public_sdk_source_vst2_x_audioeffectx_h ext;
    main_cpp -.->|imports| ext_public_sdk_source_vst2_x_audioeffectx_h
```

---

## Architecture Reference

### CPP (1 files)

#### `main.cpp`
**Path:** `main.cpp`

**Classs:**
- `ToneGenerator` (line 5) - *include <cmath> include <array> include "public.sdk/source/vst2.x/audioeffectx.h"*

**Functions:**
- `processReplacing` (line 20)
- `generateTone` (line 33)
- `canDo` (line 39)
