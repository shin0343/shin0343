# Hi, I'm Jay (Jaehyup Shin) 👋

**Software Engineer | C++/Linux Systems · AI Engineering**

I have **6+ years of experience building production software** at Hanwha Vision, spanning distributed video systems, embedded devices, and cross-platform applications. My work includes improving software performance, streamlining C++ build and release workflows, and delivering features used in real-world deployments.

I'm now pursuing an **M.S. in Artificial Intelligence at Santa Clara University**, extending that engineering background through **open-source AI contributions, retrieval-augmented generation (RAG), and AI agent systems**.

🎯 **Seeking Summer 2027 internships:** Software Engineering · AI/ML Engineering · AI Systems  
📍 San Jose, CA · San Francisco Bay Area  
🔗 [Portfolio](https://jayshin.pages.dev/) · [LinkedIn](https://www.linkedin.com/in/jay-jaehyup-shin-08843a190/) · [Email](mailto:jshin4@scu.edu)

## Highlights

- **6+ years in production engineering:** Delivered C++/Linux, embedded, and cross-platform software at Hanwha Vision, including performance and developer-workflow improvements.
- **2 merged AI open-source pull requests:** Contributed C++ memory-allocation and Python streaming fixes to **Qualcomm GenieX**.
- **Applied AI development:** Built RAG-based enterprise analysis and a local AI agent security workbench with evidence review and tool-call policies.

## Open-Source AI Contributions

**[Qualcomm GenieX](https://github.com/qualcomm/GenieX) — 2 merged pull requests**

- **[PR #1564 — C++ inference efficiency](https://github.com/qualcomm/GenieX/pull/1564):** Changed vision-language model (VLM) logits allocation from one row per token to **one row per sequence**, avoiding unused memory reservations.
- **[PR #1577 — Python streaming reliability](https://github.com/qualcomm/GenieX/pull/1577):** Fixed cancellation behavior that could stream tokens rejected by the SDK and leave streamed output inconsistent with the final result.

Both contributions were reviewed and merged by project maintainers.

## Featured AI & Software Projects

| Project | What it does and what I built | Stack |
| --- | --- | --- |
| **[RippleBrain](https://github.com/shin0343/RippleBrain)** · Enterprise Change-Impact Agent | Built an application that **traces how policy or contract changes affect related documents**, surfaces supporting evidence, and prepares actions for **human review and approval**. | Python, FastAPI, Next.js, HydraDB, RAG |
| **[AI Agent Security Lab](https://github.com/shin0343/ai-agent-security-labs)** · Security Workbench | Built a local workbench to **investigate security evidence and control AI-agent tool calls** through deny, monitor, and approval policies. **234 backend tests passed** using synthetic data. | Python, FastAPI, SQLite, React, TypeScript, pytest |
| **[ONVIF Professional Plugin](https://github.com/shin0343/onvif-professional-plugin)** · Developer Tooling | Created a Claude Code plugin for **network-camera protocol diagnostics, device-profile analysis, and conformance workflows**. | ONVIF, networking, Claude Code |

**Other projects**

- **[CardGuard](https://github.com/shin0343/cardguard)** *(team project)* — Prototyped privacy-aware payment-risk analysis using federated learning, cooperating agents, rules, and human review. **Python, Flower, React, Stripe test mode**.
- **[BridgeToCampus](https://github.com/shin0343/bridge_to_campus)** · [Live demo](https://shin0343.github.io/bridge_to_campus/) — Built an interactive 90-day transition-planning web prototype for international students.

More implementation details and case studies: **[Interactive portfolio](https://jayshin.pages.dev/)**.

## Professional Experience

**Hanwha Vision — Research Engineer → Senior Research Engineer**  
*January 2020 – March 2026*

- Developed modular **C++/Qt 6/QML** components for a distributed video management system handling **thousands of camera and server connections**.
- Built video, device-control, and update features for **Windows, macOS, and Ubuntu**; automated embedded build setup with Docker.
- Improved firmware responsiveness and C++ build workflows; administered Git branching, pull-request, and release processes used by a **50-engineer team**.
- Delivered embedded NVR functionality that **contributed to a $7.5M U.K. retail contract** and integrated an LTE modem with hardware testing in approximately **3 weeks**.

## Technical Skills

| Area | Skills and experience |
| --- | --- |
| **Software & systems** | C, C++, Linux/Unix, distributed systems, Qt 6/QML, embedded development |
| **AI & ML** | Python, RAG, AI agents, AI inference open-source contributions, machine learning coursework |
| **Backend & web** | FastAPI, REST APIs, JavaScript/TypeScript, React, Next.js, SQL |
| **Engineering workflows** | Docker, Git, GitHub Actions, CI/CD, debugging, cross-compilation |

## Education

- **Santa Clara University** — M.S. in Artificial Intelligence *(expected June 2028)*
- **Hongik University** — B.S. in Computer Engineering *(2020)*
