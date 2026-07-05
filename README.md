# Hi, I'm Ericsson 👋

**Edge & systems engineer** — embedded devices, networking, and on-device ML, plus the cloud control planes that manage device fleets. NTU CSIE grad student.

I like the boundary where software meets constrained hardware: quantized inference that fits on router-class silicon, steering decisions made on-device, and the backend that rolls all of it out safely.

## Currently working on

- **[edge-infer](https://github.com/ericsson-kuma/edge-infer)** — a tiny, zero-dependency INT8 inference runtime in C++17, with a measured optimization journey (naive → blocked GEMM, 11× speedup) and honest INT8-vs-FP32 benchmarks. [Live results ↗](https://ericsson-kuma.github.io/edge-infer/)
- **[fleet-ctl](https://github.com/ericsson-kuma/fleet-ctl)** — a Go + gRPC control plane for device fleets: registration, telemetry streaming, and staged config rollouts with health-gated guardrails and automatic rollback.
- **mesh-steer-ml** — Wi-Fi mesh client steering: an on-device ML decision path (C++, INT8) paired with a cloud rollout plane (Go/gRPC). Private for now — happy to walk through it.

## Tech I work with

| | |
|---|---|
| **Systems** | C/C++17, Go, Python, Linux, CMake, gRPC/protobuf |
| **Edge & embedded** | INT8 quantization, on-device inference (LiteRT/ONNX), microbenchmarking |
| **Networking** | Wi-Fi/802.11 (mesh, roaming/steering), client–cloud protocol design |
| **Cloud** | control-plane design, staged rollouts & guardrails, GitHub Actions CI |
| **Lab (research)** | multimodal retrieval (BM25 / DPR / embedding search), LoRA fine-tuning |

![Ericsson's GitHub stats](https://github-readme-stats.vercel.app/api?username=ericsson-kuma&show_icons=true&rank_icon=github)
