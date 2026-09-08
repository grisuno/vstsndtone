# Subsystem: misc

## main.cpp
- Layer: utility
- Doc: include <cmath> include <array> include "public.sdk/source/vst2.x/audioeffectx.h"
- Language: cpp
- Symbols:
  - `ToneGenerator` (class, line 5)
  - `processReplacing` (function, line 20) `virtual void processReplacing(float** inputs, float** outputs, VstInt32 sampleFrames)`
  - `generateTone` (function, line 33) `float generateTone()`
  - `canDo` (function, line 39) `virtual VstInt32 canDo(char* text)`
  - `setNumInputs` (function, line 10) `setNumInputs(0);`
  - `setNumOutputs` (function, line 11) `setNumOutputs(2);`
  - `setUniqueID` (function, line 12) `setUniqueID('TONE');`
  - `canProcessReplacing` (function, line 14) `canProcessReplacing();`
  - `isSynth` (function, line 15) `isSynth();`
  - `programsAreChunks` (function, line 16) `programsAreChunks();`
