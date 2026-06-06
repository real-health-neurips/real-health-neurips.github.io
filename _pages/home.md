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
  <div style="font-size:1.35rem; font-weight:600;">Proposed for NeurIPS 2026</div>
  <div style="font-size:1.05rem; margin-top:0.5rem;">December 2026 &nbsp;&bull;&nbsp; Atlanta &nbsp;&bull;&nbsp; Pending acceptance</div>
  <div style="font-size:0.95rem; margin-top:0.6rem; opacity:0.95;">From research to bedside: making AI in healthcare reliable, verifiable, private, and safe enough to deploy.</div>
</div>

## Welcome

Welcome to **ReAL-Health 2026: Reliable AI in Healthcare**, a one-day workshop proposed for the **39th Annual Conference on Neural Information Processing Systems (NeurIPS 2026)**.

Healthcare is the highest-stakes deployment frontier for modern AI. Foundation models and clinical large language models (LLMs) are entering triage, charting, prior authorization, summarization, decision support, and increasingly multi-step agentic workflows. Yet the techniques that make a model accurate on a benchmark are not the techniques that make it *deployable at the bedside*. Clinical deployment demands properties the broader ML community treats as secondary: calibrated uncertainty, faithful grounding in the patient record, fairness across protected and intersectional groups, robust behavior under distribution shift, privacy that survives federation and the right to be forgotten, security against adversarial manipulation of inputs and connected devices, traceable explanations that clinicians and regulators can audit, and meaningful human oversight when an agent acts on a patient's behalf.

ReAL-Health convenes the machine learning, healthcare informatics, formal-methods, and security and privacy communities around a single question: **how do we engineer AI systems that are reliable enough to deploy in healthcare, and how do we prove it?** The workshop is built around two complementary directions:

1. **Reliable AI by design.** Reliability and uncertainty quantification, hallucination mitigation and clinical grounding, privacy-preserving and federated learning across hospital networks, machine unlearning aligned with HIPAA and GDPR, adversarial robustness of clinical AI and connected medical devices, formal verification and assurance cases, explainability for clinical decision support, evaluation science beyond accuracy, and the safety of LLM-driven agents in real clinical workflows.

2. **Deployment, regulation, and accountability.** Deployment experience reports from hospitals and industry, regulatory frameworks (FDA AI/ML SaMD, EU AI Act, NIST AI RMF) reframed as concrete engineering workflows, auditing and assurance for clinical AI, and human-AI collaboration that preserves agency and accountability.

<p align="center">
  <a href="https://real-health-neurips.github.io/">ReAL-Health 2026</a> &bull; A
  <a href="https://neurips.cc/Conferences/2026">NeurIPS 2026</a> Workshop
</p>

**Workshop date:** December 2026, pending NeurIPS workshop acceptance (notification July 11, 2026)
**Location:** Atlanta (pending NeurIPS venue assignment)
**Format:** In-person, approximately 8 hours
**Primary contacts:** sumon@case.edu, shibbir@txstate.edu

> **Note:** This site is under construction. Items marked **TBA** will be updated after the NeurIPS workshop notification on July 11, 2026, and as the program is finalized.

---

### Organizing Committee

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:3rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/islam.png' | relative_url }}"
         alt="Md Tauhidul Islam" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Md Tauhidul Islam</strong><br><em>Stanford University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/avanti.jpg' | relative_url }}"
         alt="Avanti Bhandarkar" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Avanti Bhandarkar</strong><br><em>Mayo Clinic, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/sumon.jpg' | relative_url }}"
         alt="Sumon Biswas" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Sumon Biswas</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/amit.jpg' | relative_url }}"
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

### Invited Speakers

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:3rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/xiaofeng.jpg' | relative_url }}"
         alt="Xiaofeng Wang" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Xiaofeng Wang</strong><br><em>Cleveland Clinic, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/robert.jpg' | relative_url }}"
         alt="Robert Davis" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Robert Davis</strong><br><em>University of Tennessee Health Science Center, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/anant.jpg' | relative_url }}"
         alt="Anant Madabhushi" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Anant Madabhushi</strong><br><em>Georgia Tech &amp; Emory University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/ritambhara.jpg' | relative_url }}"
         alt="Ritambhara Singh" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Ritambhara Singh</strong><br><em>Brown University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/vipin.jpg' | relative_url }}"
         alt="Vipin Chaudhary" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Vipin Chaudhary</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/satish.jpg' | relative_url }}"
         alt="Satish E. Viswanath" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Satish E. Viswanath</strong><br><em>Emory University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/jing.jpg' | relative_url }}"
         alt="Jing Li" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Jing Li</strong><br><em>Case Western Reserve University, USA</em>
  </div>

</div>

Full speaker details on the [Speakers page]({{ '/speakers/' | relative_url }}).

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

### Shared Task

ReAL-Health 2026 will host a community shared task on **reliability and safety in patient-facing LLMs**, built on the publicly available HealthBench rubric. Participants train or prompt models, or build safety guardrails, evaluated against physician-written rubrics covering safety, factuality, refusal behavior, and communication. Top systems present spotlight talks at the workshop, and **Best System** and **Best Student System** awards will be announced at closing. Participation does not require a paper submission.

Full task details, dataset, and timeline on the [Shared Task page]({{ '/shared-task/' | relative_url }}).

---

### Program

The full one-day program spans approximately 8 hours, mixing keynotes, contributed sessions, poster sessions, a panel, and a cross-community working discussion. See the [Schedule page]({{ '/schedule/' | relative_url }}).

---

### Technical Program Committee Members

Our Technical Program Committee comprises researchers spanning machine learning reliability, clinical informatics, security and privacy, federated learning, and software engineering for AI. Members below have confirmed their participation in reviewing for ReAL-Health 2026.

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin-bottom:3rem;">

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/akond.jpg' | relative_url }}"
         alt="Akond Rahman" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Akond Rahman</strong><br><em>Auburn University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/dalal.jpg' | relative_url }}"
         alt="Dalal Alharthi" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Dalal Alharthi</strong><br><em>The University of Arizona, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/praneeth.jpg' | relative_url }}"
         alt="Praneeth Narayanamurthy" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Praneeth Narayanamurthy</strong><br><em>Alcon, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/niloufar.jpg' | relative_url }}"
         alt="Niloufar Alipour Talemi" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Niloufar Alipour Talemi</strong><br><em>Clemson University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/sayeed.jpg' | relative_url }}"
         alt="Sayeed Shafayet Chowdhury" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Sayeed Shafayet Chowdhury</strong><br><em>Indiana University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/ratna.jpg' | relative_url }}"
         alt="Ratna Kandala" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Ratna Kandala</strong><br><em>University of Kansas, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/mahmoud.jpg' | relative_url }}"
         alt="Mahmoud Nazzal" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Mahmoud Nazzal</strong><br><em>Old Dominion University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/farah.jpg' | relative_url }}"
         alt="Farah Ferdaus" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Farah Ferdaus</strong><br><em>Lamar University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/akram.jpg' | relative_url }}"
         alt="Akram Mohammed" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Akram Mohammed</strong><br><em>UT Health Science Center, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/aruna.jpg' | relative_url }}"
         alt="Aruna Jayasena" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Aruna Jayasena</strong><br><em>UMass Amherst, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/filiz.jpg' | relative_url }}"
         alt="Filiz Bunyak Ersoy" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Filiz Bunyak Ersoy</strong><br><em>University of Missouri, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/zhonghao.jpg' | relative_url }}"
         alt="Zhonghao Liao" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Zhonghao Liao</strong><br><em>Milwaukee School of Engineering, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/silpa.jpg' | relative_url }}"
         alt="Silpa Babu" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Silpa Babu</strong><br><em>University of Iowa, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/amitseal.jpg' | relative_url }}"
         alt="Amit Seal Ami" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Amit Seal Ami</strong><br><em>University of South Florida, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/nigar.jpg' | relative_url }}"
         alt="Nigar Khasayeva" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Nigar Khasayeva</strong><br><em>Georgia State University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/breno.jpg' | relative_url }}"
         alt="Breno Dantas Cruz" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Breno Dantas Cruz</strong><br><em>Tulane University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/anwang.jpg' | relative_url }}"
         alt="An Wang" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. An Wang</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/erman.jpg' | relative_url }}"
         alt="Erman Ayday" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Erman Ayday</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/nasik.jpg' | relative_url }}"
         alt="Nasik Muhammad Nafi" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Nasik Muhammad Nafi</strong><br><em>Oak Ridge National Laboratory, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/emad.jpg' | relative_url }}"
         alt="Emad Shihab" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Emad Shihab</strong><br><em>Concordia University, Canada</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/sayma.jpg' | relative_url }}"
         alt="Sayma Sultana" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Sayma Sultana</strong><br><em>Tulane University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/gias.jpg' | relative_url }}"
         alt="Gias Uddin" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Gias Uddin</strong><br><em>York University, Canada</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/kevin.jpg' | relative_url }}"
         alt="Kevin Xu" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Kevin Xu</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/jaydeb.jpg' | relative_url }}"
         alt="Jaydeb Sarker" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Jaydeb Sarker</strong><br><em>University of Nebraska at Omaha, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/abdullah.jpg' | relative_url }}"
         alt="Abdullah Al Maruf" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Abdullah Al Maruf</strong><br><em>California State University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/yuyin.jpg' | relative_url }}"
         alt="Yu Yin" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Yu Yin</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/iftekhar.jpg' | relative_url }}"
         alt="Iftekhar Ahmed" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Iftekhar Ahmed</strong><br><em>University of California, Irvine, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/sanmukh.jpg' | relative_url }}"
         alt="Sanmukh Kuppannagari" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Sanmukh Kuppannagari</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/masud.jpg' | relative_url }}"
         alt="Masud Rahman" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Masud Rahman</strong><br><em>Dalhousie University, Canada</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/soumya.jpg' | relative_url }}"
         alt="Soumya Ray" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Soumya Ray</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/jingma.jpg' | relative_url }}"
         alt="Jing Ma" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Jing Ma</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/yining.jpg' | relative_url }}"
         alt="Yining She" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Yining She</strong><br><em>Carnegie Mellon University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/shuai.jpg' | relative_url }}"
         alt="Shuai Xu" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Shuai Xu</strong><br><em>Case Western Reserve University, USA</em>
  </div>

  <div style="text-align:center; width:160px;">
    <img src="{{ '/assets/img/people/feixiong.jpg' | relative_url }}"
         alt="Feixiong Cheng" style="width:100px; height:100px; object-fit:cover; border-radius:50%;" />
    <br><strong>Dr. Feixiong Cheng</strong><br><em>Cleveland Clinic, USA</em>
  </div>

</div>

The full program committee is also listed on the [Organization page]({{ '/organization/' | relative_url }}).
