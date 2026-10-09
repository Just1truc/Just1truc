# Justin Duc
**ML Systems & Kernel Optimization Researcher**

justin.duc@galiad-research.com | +33 6 63 52 82 16 | Lyon, France  
[LinkedIn: justin-duc](https://linkedin.com/in/justin-duc) | [GitHub: Just1truc](https://github.com/Just1truc) | [HuggingFace: JustinDuc](https://huggingface.co/JustinDuc)

---

## Technical Skills
**Core ML Systems:** OpenAI Triton, NVIDIA TensorRT 10.x, CUDA C++, ONNX Runtime, LLM Inference, PyTorch Compiler  
**Low-Level & Hardware:** PTX ISA Assembly, SymPy AST, Nsight Systems Profiling, Target Architectures (H100, A100, Blackwell sm_120a)  
**Infrastructure & Languages:** C++17/20, Python, Docker, GitHub Actions CI/CD, React, NestJS  

---

## Experience

### ML Optimization Consultant | Audioshake
*Remote (California) | 09/2025 – 04/2026*
* Engineered high-throughput inference pipelines across TensorRT 10.x, OpenAI Triton, Helion, `torch.compile`, and ONNX, targeting **NVIDIA H100 and A100** architectures.
* Authored specialized Triton custom ops for audio source separation models, maximizing Tensor Core utilization and profiling with **Nsight Systems** to reduce VRAM memory bandwidth by an estimated **40%** and cut kernel launch latency by **3x**.
* Developed automated transpilation frameworks bridging custom Python `@triton.jit` operators directly to ONNX Runtime (`OrtCustomOp`) and TensorRT C++ plugins, increasing inference throughput by up to **2.5x** compared to eager PyTorch execution.

### Owner & Technical Founder | Eclat
*Lyon, France | 01/2024 – Present*
* Architected automated B2B 3D jewelry customization engine, designing Python scrapers interfacing directly with industrial Materialise manufacturing APIs.
* Deployed the entire full-stack application using **Docker containers** and **GitHub Actions CI/CD pipelines** orchestrated for high availability, handling procedural Blender 3D rendering pipelines and achieving a **20%** field conversion rate.
* Formulated financial pricing algorithms accounting for live precious metal spot prices, URSSAF tax rates (12.3%), and €50 Minimum Order Value (MOV) supplier cliffs.

### Intern Teacher | EPITECH
*Lyon, France | 09/2025 – 02/2026*
* Supervised, graded, and mentored 50+ computer science students on Machine Learning, Deep Learning architectures, and C++ systems programming.

### AI Developer | Wanadev
*Lyon, France | 02/2024 – 06/2024*
* Formulated mathematical game balancing simulations and AI agent decision models for a commercial autobattler game.

### Teacher | ISEG
*Lyon, France | 01/2024 – 03/2024*
* Taught relational database architecture (SQL), PHP, and web development fundamentals to undergraduate students.

### Full-Stack Developer | SNB Technologies
*Remote | 10/2023 – 02/2024*
* Developed administrative software and backend analytics pipelines for enterprise conversational AI chatbots.

### ML Research Developer | POC
*Lyon, France | 10/2022 – 06/2023*
* Led 6-month AI research initiatives on VQ-VAE generative style transfer and partnered with Effiscience on neural network feature interpretability.

### Full-Stack Developer | Visiativ PLM
*Bron, France | 06/2022 – 12/2022*
* Refactored and ported a legacy enterprise Java desktop PLM application into a modern, high-performance Angular web application.

---

## Research & Projects

### KernelLens: Triton-to-C++ Compiler | Lead Author (Galiad Research)
*02/2026 – 10/2026 | [Zenodo DOI: 10.5281/zenodo.23194523](https://doi.org/10.5281/zenodo.23194523)*
* Architected an open-source 4-phase compiler converting PyTorch `@triton.jit` kernels to ONNX Runtime & TensorRT C++ plugins via PTX extraction and CUDA Driver API.
* Implemented SymPy AST grid transpilation, 16-byte CUDA alignment guards, and **Blackwell (`sm_120a`) PTX ISA** version clamping, specifically optimizing Flash Attention execution on next-gen hardware.
* Achieved **3.4x–7.0x speedups** over eager PyTorch across LLaMA 3, Qwen 2.5, and Liger-Kernels with exact numerical parity (MaxDiff=0), establishing the tool as a robust deployment artifact.

### TreaT: Tree Attention for Retrieval | Lead Author (Tsinghua University)
*01/2025 – 06/2025*
* Designed a novel binary memory tree attention replacing dense O(N²) comparisons with O(log N) logarithmic-time routing over hierarchical summaries.
* Formulated analytical routing error propagation models; trained via self-attention distillation with Reciprocal-Value Scoring.

### Saute: Utterance Embeddings | Lead Author (Tsinghua University)
*01/2025 – 06/2025*
* Developed a linear-attention Transformer architecture leveraging speaker-sensitive memory banks for efficient utterance-level context modeling.

---

## Education

**Tsinghua University** | *Beijing, China (09/2024 – 07/2025)*
* Study Abroad in AI & NLP: Advanced research in Deep Learning, NLP, Algorithm Design, Big Data Intelligence, and Quantitative Finance.

**EPITECH** | *Lyon, France (2021 – 2026)*
* Expert in Computer Science: Master's level degree in Software Engineering, Architecture, and Systems.

---

## Awards & Languages
* **Awards:** Pioneer Award 2024 (Chengdu 80 Fintech Design Competition at Tsinghua University)
* **Languages:** French (Native/Bilingual), English (Fluent/Professional)
