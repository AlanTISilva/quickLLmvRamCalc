# LLM VRAM Calculator

**Simple standalone HTML tool** to estimate VRAM usage for running LLMs.

## Features
- Model weights VRAM (any param count + Q2_K → FP16)
- KV cache calculator (context + FP16/Q8_0)
- Accurate architecture presets (Llama, Qwen2/3.5/3.6, Mistral, etc.)
- Canvas visual bar + GPU fit checker

## Usage
1. Open `llm-vram-calculator.html` in any browser
2. All values update live
3. Select presets for correct layers/KV dim

Made for local LLM users (llama.cpp / GGUF).

Refresh to get latest presets.
