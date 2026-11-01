# Hi, I'm Jay (Jaehyup Shin) 👋

**Software Engineer | C++/Linux & Cross-Platform Systems | AI Infrastructure & LLM Serving**

I'm a software engineer with **6+ years of experience building production C++/Linux, embedded, and cross-platform systems** at Hanwha Vision. I work on performance, reliability, and the engineering needed to deliver complex software at scale.

I'm now pursuing an **M.S. in Artificial Intelligence at Santa Clara University**, extending that systems background into AI inference and distributed LLM infrastructure through merged open-source contributions.

🎯 **Seeking Summer 2027 internships:** Software Engineering · AI/ML Engineering · AI Infrastructure / ML Systems  
📍 **San Jose, CA · SF Bay Area**  
🔗 [Portfolio](https://jayshin.pages.dev/) · [LinkedIn](https://www.linkedin.com/in/jay-jaehyup-shin-08843a190/) · [Email](mailto:jshin4@scu.edu)

## Engineering Highlights

- **Production systems:** Developed C++/Qt 6/QML components for multi-server video management supporting **thousands of camera and server connections**, along with REST-backed device management.
- **Measured performance improvements:** Reduced firmware-information load/reset latency **67% (1,174 → 386 ms)** and C++ build time **13.9%**, with build results validated across five benchmark runs per configuration.
- **Engineering at scale:** Managed Git branching, code-review, and release workflows for a **50-engineer team**, including biweekly releases and hotfixes.
- **Cross-platform and embedded:** Built software for **Windows, macOS, and Ubuntu**; integrated embedded NVR capabilities and automated SoC toolchain setup with Docker.

## Merged Open-Source Contributions

**[Qualcomm GenieX](https://github.com/qualcomm/GenieX) · AI inference runtime**

- [**PR #1564 · C++ / VLM logits memory allocation**](https://github.com/qualcomm/GenieX/pull/1564): Reduced unnecessary logits memory reservations by allocating one row per sequence.
- [**PR #1577 · Python / streaming reliability**](https://github.com/qualcomm/GenieX/pull/1577): Fixed streaming cancellation behavior and prefix-reuse issues.

**[llm-d Router](https://github.com/llm-d/llm-d-router) · Distributed LLM inference**

- [**PR #3677 · Go / P2P KV-cache propagation**](https://github.com/llm-d/llm-d-router/pull/3677): Preserved validated cache sources across disaggregated encode/prefill/decode stages; added 10 HTTP regression scenarios.

**[AWS SageMaker HyperPod CLI](https://github.com/aws/sagemaker-hyperpod-cli) · Cloud ML tooling**

- [**PR #471 · CLI correctness & regression tests**](https://github.com/aws/sagemaker-hyperpod-cli/pull/471): Aligned CloudFormation stack output, CLI help, and SDK documentation; added regression tests.

## Selected Project

- **[CardGuard](https://github.com/shin0343/cardguard) · Secure multi-agent collaboration:** Worked on a five-person hackathon team to develop prompt-injection defenses, rogue-node safeguards, and secure agent coordination for privacy-preserving payment-fraud analysis.

## Technical Skills

- **Languages:** C++, C, Python, Go, SQL, JavaScript
- **Systems & tools:** Linux, embedded systems, Qt 6/QML, Docker, Git/GitHub Actions, CI/CD, Windows, macOS
- **AI & backend:** Machine Learning, LLM inference, KV cache, distributed systems, RAG, AI agents, FastAPI, REST APIs

## Education

- **Santa Clara University** — M.S. in Artificial Intelligence *(expected June 2028)*
- **Hongik University** — B.S. in Computer Engineering *(2020)*
