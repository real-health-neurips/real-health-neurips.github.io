---
layout: default
title: "ReAL-Health 2026"
permalink: /
nav_order: 1
---

<!-- Logo & Title side by side -->
<div style="display:flex; align-items:center; justify-content:center; gap:1.5rem; margin:2rem 0; flex-wrap:wrap;">
  <img
    src="{{ '/assets/img/realhealth-logo.svg' | relative_url }}"
    alt="ReAL-Health 2026 Logo"
    style="width:120px; height:auto;"
  />
  <h1 style="margin:0; font-size:2.2rem; line-height:1.2;">
    ReAL-Health 2026: Reliable AI in Healthcare
  </h1>
</div>

<!-- Hero banner -->
<div style="text-align:center; margin-bottom:2.5rem; padding:2.5rem 1rem; border-radius:14px;
            background:linear-gradient(135deg,#0EA5A5 0%,#066B82 100%); color:#fff;">
  <div style="font-size:1.35rem; font-weight:600;">A NeurIPS 2026 Workshop</div>
  <div style="font-size:1.05rem; margin-top:0.5rem;">December 2026 &nbsp;&bull;&nbsp; Venue TBA (Atlanta, Paris, or Sydney)</div>
  <div style="font-size:0.95rem; margin-top:0.6rem; opacity:0.95;">From research to bedside: making AI in healthcare reliable, verifiable, private, and safe enough to deploy.</div>
</div>

## Welcome

Welcome to **ReAL-Health 2026: Reliable AI in Healthcare**, a one-day workshop at the **39th Annual Conference on Neural Information Processing Systems (NeurIPS 2026)**.

Healthcare is the highest-stakes deployment frontier for modern AI. Foundation models and clinical large language models (LLMs) are entering triage, charting, prior authorization, summarization, decision support, and increasingly multi-step agentic workflows. Yet the techniques that make a model accurate on a benchmark are not the techniques that make it *deployable at the bedside*. Clinical deployment demands properties the broader ML community treats as secondary: calibrated uncertainty, faithful grounding in the patient record, fairness across protected and intersectional groups, robust behavior under distribution shift, privacy that survives federation and the right to be forgotten, security against adversarial manipulation of inputs and connected devices, traceable explanations that clinicians and regulators can audit, and meaningful human oversight when an agent acts on a patient's behalf.

ReAL-Health convenes the machine learning, healthcare informatics, formal-methods, and security and privacy communities around a single question: **how do we engineer AI systems that are reliable enough to deploy in healthcare, and how do we prove it?** The workshop is built around two complementary directions:

1. **Reliable AI by design.** Reliability and uncertainty quantification, hallucination mitigation and clinical grounding, privacy-preserving and federated learning across hospital networks, machine unlearning aligned with HIPAA and GDPR, adversarial robustness of clinical AI and connected medical devices, formal verification and assurance cases, explainability for clinical decision support, evaluation science beyond accuracy, and the safety of LLM-driven agents in real clinical workflows.

2. **Deployment, regulation, and accountability.** Deployment experience reports from hospitals and industry, regulatory frameworks (FDA AI/ML SaMD, EU AI Act, NIST AI RMF) reframed as concrete engineering workflows, auditing and assurance for clinical AI, and human-AI collaboration that preserves agency and accountability.

<p align="center">
  <a href="https://real-health-neurips.github.io/">ReAL-Health 2026</a> &bull; A
  <a href="https://neurips.cc/Conferences/2026">NeurIPS 2026</a> Workshop
</p>

**Workshop date:** December 2026 (specific day TBA after NeurIPS venue assignment)
**Location:** TBA, one of NeurIPS 2026's venues (Atlanta, Paris, or Sydney)
**Format:** In-person, approximately 8 hours
**Primary contacts:** sumon@case.edu, shibbir@txstate.edu

> **Note:** This site is under construction. Items marked **TBA** will be updated after the NeurIPS workshop notification on July 11, 2026, and as the program is finalized.

---

### Organizing Committee

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:3rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/md_tauhidul_islam.png' | relative_url }}"
         alt="Md Tauhidul Islam" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Md Tauhidul Islam</strong><br><em>Stanford University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/avanti_bhandarkar.jpeg' | relative_url }}"
         alt="Avanti Bhandarkar" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Avanti Bhandarkar</strong><br><em>Mayo Clinic, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/sumon.jpg' | relative_url }}"
         alt="Sumon Biswas" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Sumon Biswas</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/amit_kumar_sikder.jpg' | relative_url }}"
         alt="Amit Kumar Sikder" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Amit Kumar Sikder</strong><br><em>Iowa State University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/shahnewaz.jpg' | relative_url }}"
         alt="Shahnewaz Karim Sakib" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Shahnewaz Karim Sakib</strong><br><em>University of Tennessee at Chattanooga, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/anindya.jpg' | relative_url }}"
         alt="Anindya Bijoy Das" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Anindya Bijoy Das</strong><br><em>University of Akron, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/sahmed.jpg' | relative_url }}"
         alt="Shibbir Ahmed" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Shibbir Ahmed</strong><br><em>Texas State University, USA</em>
  </div>

</div>

Full bios are available on the [Organization page]({{ '/organization/' | relative_url }}).

---

## Participation

ReAL-Health welcomes original short papers, extended abstracts, deployment experience reports, datasets, benchmarks, and position papers. Speculative work and negative results are explicitly in scope.

### Submission Types
- **Short papers** (4 pages plus references): novel research, methods, or systems.
- **Extended abstracts** (2 pages): work in progress, position papers, tool or benchmark previews.
- **Experience reports**: deployment lessons from hospitals, industry, or regulators.

- **Submission site:** OpenReview (link TBA)
- **Review process:** Double-blind, three program-committee reviews per submission, structured rubric.

### Important Dates (NeurIPS 2026 timeline)

| Milestone | Date |
| --- | --- |
| Workshop acceptance notification (to organizers) | July 11, 2026 |
| CFP and OpenReview site live | Within two weeks of acceptance |
| Suggested submission deadline | August 29, 2026 (AoE) |
| Author notification (mandatory) | September 29, 2026 (AoE) |
| Camera-ready and program | Late October 2026 |
| Workshop | December 2026 |

> All accepted contributions are non-archival per NeurIPS workshop policy and may appear on OpenReview at authors' option.

Full details on the [Call for Participation page]({{ '/call-for-papers/' | relative_url }}).

---

### Invited Speakers

The confirmed invited speakers include leading voices from medical AI, biomedical informatics, healthcare privacy, and genomics. See the full slate on the [Speakers page]({{ '/speakers/' | relative_url }}).

---

### Program

The full one-day program spans approximately 8 hours, mixing keynotes, contributed sessions, poster sessions, a panel, and a cross-community working discussion. See the [Schedule page]({{ '/schedule/' | relative_url }}).
