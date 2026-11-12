# 05. FreeLLM WebGPU Hub (`Omi811/freellm-hub`)

> In-browser zero-cloud LLM execution powered by WebGPU and WebAssembly

- **⚡ Evo Studio Live (GitHub Pages)**: [https://omi811.github.io/om-panchal-studio/?edition=evo&project=freellm-hub](https://omi811.github.io/om-panchal-studio/?edition=evo&project=freellm-hub)
- **🏛️ GitHub Legacy Studio**: [https://omi811.github.io/freellm-hub/](https://omi811.github.io/freellm-hub/)
- **Codebase**: [https://github.com/Omi811/Omi811.github.io/tree/main/freellm-hub](https://github.com/Omi811/Omi811.github.io/tree/main/freellm-hub)
- **Telemetry**: `11ms` DOM · `100 / 100` Lighthouse · `$0 / mo` Cloud Burn
- **Commercial Ticket**: **₹12,500** ($150) — Enterprise private on-prem setup (₹12,500 / $150) & community backing

## Problem Solved
Enterprises and privacy-conscious teams cannot send sensitive legal, medical, or proprietary source code to external OpenAI or Anthropic cloud endpoints.

## Architecture Summary
Downloads quantized open-weight models once into browser cache and executes token inference directly on the client GPU via WebGPU shaders with zero network egress.

## Key Capabilities
- 100% air-gapped capable inference after initial model weight caching
- Hardware-accelerated WebGPU tensor execution directly inside Chrome/Edge
- Zero per-token API cost regardless of team usage volume
- Custom enterprise deployment with pre-configured domain system prompts
