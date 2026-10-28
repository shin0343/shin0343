# Hi, I'm Jay (Jaehyup Shin) 👋

**Software Engineer | C++/Linux & Embedded Systems | AI Infrastructure**

I'm a software engineer with **6+ years of experience building production C++/Linux software** at Hanwha Vision, spanning multi-server video systems, embedded devices, and cross-platform applications. I focus on **solving performance and reliability problems with measurable, tested engineering changes**.

I'm now pursuing an **M.S. in Artificial Intelligence at Santa Clara University**, extending that systems background through **merged AI inference open-source contributions** and hands-on AI systems projects.

🎯 **Seeking Summer 2027 internships:** Software Engineering · C++/Embedded Systems · AI Infrastructure / ML Systems  
📍 **San Jose, California** · San Francisco Bay Area  
🔗 [Portfolio](https://jayshin.pages.dev/) · [LinkedIn](https://www.linkedin.com/in/jay-jaehyup-shin-08843a190/) · [Email](mailto:jshin4@scu.edu)

## Engineering Highlights

- **Production systems:** Developed modular **C++/Qt 6/QML** components for a multi-server video management platform supporting **thousands of camera and server connections**, including REST-backed device management.
- **Performance optimization:** Reduced firmware-information load/reset latency **67% (1,174 ms → 386 ms)** using parallel execution threads; cut C++ build time **13.9%** with precompiled headers, validated across five benchmark runs per configuration.
- **Engineering at team scale:** Managed Git branching, reviews, and release workflows for a **50-engineer team**, supporting biweekly releases and urgent hotfixes.
- **Embedded and cross-platform development:** Integrated and hardware-tested NVR LTE modem functionality in approximately **three weeks**; built software for **Windows, macOS, and Ubuntu** and automated embedded SoC toolchain setup with Docker.

## Merged Open-Source Contributions

**[Qualcomm GenieX](https://github.com/qualcomm/GenieX) — AI inference runtime**

- **[PR #1564 · C++ / VLM memory allocation](https://github.com/qualcomm/GenieX/pull/1564):** Changed logits allocation from per-token rows to one row per sequence, avoiding unused memory reservations.
- **[PR #1577 · Python / streaming reliability](https://github.com/qualcomm/GenieX/pull/1577):** Fixed cancellation behavior that could emit SDK-rejected tokens and leave streamed output inconsistent with the final result; addressed prefix-reuse issues.

**[AWS SageMaker HyperPod CLI](https://github.com/aws/sagemaker-hyperpod-cli) — developer tooling**

- **[PR #471 · CLI correctness and regression tests](https://github.com/aws/sagemaker-hyperpod-cli/pull/471):** Aligned CloudFormation stack output, CLI help, and SDK documentation, with regression tests.

## Selected Projects

- **[CardGuard](https://github.com/shin0343/cardguard) · Collaborative AI Security:** Worked in a **five-person hackathon team** on prompt-injection defenses, rogue-node safeguards, and agent coordination for privacy-preserving payment-risk analysis.
- **[ONVIF Professional Plugin](https://github.com/shin0343/onvif-professional-plugin) · Developer Tooling:** Built a Claude Code plugin for network-camera protocol diagnostics, device-profile analysis, and conformance workflows.
- **[AI Agent Security Labs](https://github.com/shin0343/ai-agent-security-labs) · Security Workbench:** Implemented tool-call policies and evidence auditing; **234 backend tests passed** using synthetic data.
- **[RippleBrain](https://github.com/shin0343/RippleBrain) · Enterprise Change-Impact Agent:** Built a FastAPI/RAG application that connects retrieved evidence to change-impact analysis and **human review and approval**.

## Technical Skills

- **Languages:** C++, C, Python, SQL, JavaScript, TypeScript
- **Systems & engineering:** Linux, embedded systems, Qt 6/QML, multithreading, Docker, Git/GitHub Actions, CI/CD, REST APIs, Windows, macOS
- **AI & backend:** Machine Learning, LLM inference, RAG, AI agents, FastAPI, Next.js

## Education & Community

- **Santa Clara University** — M.S. in Artificial Intelligence *(expected June 2028)*
- **Hongik University** — B.S. in Computer Engineering *(2020)*

**More about my engineering work:** [Interactive portfolio](https://jayshin.pages.dev/)
