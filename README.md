## Hi, I'm Roopanshu Gupta

Software Engineering student at **Delhi Technological University** ('28, CGPA 9.67) and **ML Research Intern** at DTU's Machine Learning Research Lab.

I build **LLM agents and the benchmarks that grade them**, and I do research on **generative models for satellite imagery**.

**[📄 Resume (PDF)](Roopanshu_Gupta_Resume.pdf)** · [LinkedIn](https://www.linkedin.com/in/roopanshugupta/) · [Email](mailto:roopanshugupta0512@gmail.com) · [LeetCode](https://leetcode.com/u/RoopanshuSD/) · [Codeforces](https://codeforces.com/profile/RoopanshuSD/)

---

### Featured work

**Agents & evaluation**

| Project | What it is | Measured result |
|---|---|---|
| [cloud-remediation-agent](https://github.com/RoopanshuSD/cloud-remediation-agent) | Policy-gated incident-remediation agent + **RemediationBench**: sandboxed AWS incidents graded by hidden state verifiers | Code-enforced verify stage cut false-success **29% → 0%** (fixed-prior planner); gate blocked 2/2 unsafe shortcuts |
| [unified-data-mcp-server](https://github.com/RoopanshuSD/unified-data-mcp-server) | Remote MCP server: read-only, audited agent access to SQL + REST, JWT resource-server auth, RBAC | SQL guard blocked **48/48** red-team attacks, 0/18 false positives; 92 tests |
| [datamind](https://github.com/RoopanshuSD/datamind) | Local-LLM exploratory data analysis: FK inference via graph modelling, anomaly flags | |

**ML research (computer vision · remote sensing)**

| Project | What it is | Result |
|---|---|---|
| [CAF-OTSRNET](https://github.com/RoopanshuSD/CAF-OTSRNET) | Cross-attention fusion network: optical-guided thermal super-resolution | 31 dB PSNR · 0.85 SSIM on Landsat-8 |
| [SAR-to-EO-Diffusion](https://github.com/RoopanshuSD/SAR-to-EO-Diffusion) | ControlNet on Stable Diffusion: radar (SAR) → optical image translation | |
| [SAR-to-EO CycleGAN](https://github.com/RoopanshuSD/SAR-to-EO-image-translation-using-CycleGAN) | Lightweight attention CycleGAN with Charbonnier / MS-SSIM / perceptual losses | |
| [retinanet-scratch](https://github.com/RoopanshuSD/retinanet-scratch) | RetinaNet re-implemented from scratch (ResNet-50 + FPN, focal loss, anchors, NMS) | |

**Products & hackathons**

| Project | What it is |
|---|---|
| [FinSight](https://github.com/RoopanshuSD/FinSight) · [demo](https://fin-sight-v3.vercel.app/) | NatWest Code for Purpose (**top 53 of 2,000+ teams**, team project): FastAPI forecasting with conformal intervals + LLM scenario parsing |
| [Driver-Pulse](https://github.com/RoopanshuSD/Driver-Pulse) · [demo](https://apprealtimedemopy-ga6nxjkdbmnprgyoapji7e.streamlit.app/) | Rideshare driver intelligence: fuses motion, cabin-audio and earnings telemetry into real-time shift insights |

### Experience

- **ML Research Intern**, Machine Learning Research Lab, DTU (Jan 2026 – present): CycleGAN and conditional diffusion models for SAR-to-optical translation (PSNR 15 → 31.58 dB, SSIM 0.18 → 0.87); 1TB+ satellite-imagery pipeline; S3 + HPC multi-GPU I/O optimisation.
- **5G AI Systems Intern**, DoT 5G Use Case Lab (Jun – Jul 2025): YOLOv8 traffic analytics (97.5% mAP@0.50), FP16 quantization for 5G edge deployment.

### Recognition

First Prize, DTU Summer School on AI (with Adobe) · National Finalist, Smart India Hackathon 2025 (ISRO problem statement) · ISI Entrance AIR 104 · JEE Main AIR 7997 · Departmental Rank 1 (Sem 2)

### Toolbox

`Python` `C++` `PyTorch` `Claude API` `Model Context Protocol` `FastAPI` `PostgreSQL` `sqlglot` `Docker` `AWS` `Linux / HPC` `Git`

---

*Open to internships in AI agents, evaluation, applied ML and research engineering. Remote, or onsite for Winter 2026 / Summer 2027.*
