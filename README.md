# CoDynamics Lab Corporation

**Accelerating LLM Inference Through Learned Compression**

---

## CDLaC Technology

CDLaC is a proprietary inference acceleration technology that enables a **"Fast Read / Standard Write"** architecture for transformer models.

### Verified Performance (A100-80GB, January 2026)

| Metric | CDLaC | Baseline | Speedup |
|--------|-------|----------|---------|
| Prefill Throughput | 16,904 tok/s | 7,866 tok/s | **2.15x** |
| Decode Throughput | 37.5 tok/s | 26.5 tok/s | **1.42x** |
| E2E Latency (8K context) | 1.84s | 2.93s | **1.59x** |
| Peak VRAM | 17.8 GB | 19.9 GB | **-10%** |

### Quality Benchmarks

| Benchmark | CDLaC | Baseline | Delta |
|-----------|-------|----------|-------|
| LAMBADA (accuracy) | 70.97% | 65.57% | **+5.40** |
| ARC-Easy | 80.47% | 69.95% | **+10.52** |
| PIQA | 79.38% | 76.77% | **+2.61** |
| Winogrande | 73.80% | 70.48% | **+3.32** |

---

## Repositories

| Repository | Description |
|------------|-------------|
| [cdlac-benchmarks](https://github.com/CoDynamicsLab/cdlac-benchmarks) | Public benchmark results and methodology |
| [cdlac-demo](https://github.com/CoDynamicsLab/cdlac-demo) | Interactive demo notebook |

---

## Contact

- **Website:** [codynamicslab.com](https://www.codynamicslab.com)
- **Founder:** [Mike Holford](https://www.linkedin.com/in/mike-holford/) (13 US Patents)
- **Email:** mike@codynamicslab.com

---

*CoDynamics Lab Corporation (Delaware C-Corp) | Gilbert, AZ*
