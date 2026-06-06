---
layout: page
title: "Shared Task"
permalink: /shared-task/
nav: true
nav_order: 4
nav_title: "Shared Task"
---

# Shared Task: Reliability and Safety in Patient-Facing LLMs

> **Note:** This shared task will become active upon NeurIPS workshop acceptance. Notification of acceptance is expected on **July 11, 2026**. The task description, dataset selection, and timeline below describe the planned task and will be confirmed at that time.

## Overview

ReAL-Health 2026 will host a community shared task on **reliability and safety in patient-facing large language models**, the deployment setting that is currently moving fastest from research into clinical practice and where reliability failures are most visible to patients and clinicians. The task is designed to be approachable, reproducible, and aligned with how clinical AI is actually evaluated in practice.

The shared task is built on **HealthBench**, the publicly released benchmark of approximately 5,000 realistic patient-facing health conversations annotated by physicians with rubrics covering safety, factuality, completeness, refusal behavior, and communication quality. Building on an existing high-quality benchmark, rather than constructing a new dataset, lets the task focus on methods development and evaluation rigor within the workshop's timeline.

## Tracks

The shared task has two tracks. Participation in either or both is welcome.

**Track 1: Safety-focused evaluation.** Teams submit either a fine-tuned or prompted language model, or a separate safety classifier/guardrail that takes a model output and predicts whether it satisfies the HealthBench safety rubric. The guardrail sub-track is of particular interest, since deployable guardrails for patient-facing systems are an underexplored area in the literature.

**Track 2: Red-teaming.** Teams submit adversarial prompts that elicit safety failures from a public reference model on HealthBench's safety dimensions. The best red-team set will be released as a community artifact, with credit to contributing teams.

## Evaluation

Submissions are evaluated against the HealthBench physician-written rubrics, with scores reported for each rubric dimension (safety, factuality, refusal, communication). Track 1 submissions are scored on rubric performance; Track 2 submissions are scored on the rubric-failure rate they elicit, with manual organizer review for spurious or out-of-scope prompts.

A reproducible evaluation script and starter notebook will be released at task launch. Teams submit either a model checkpoint (or HuggingFace handle), a callable API, or, for the guardrail sub-track, a classifier function, alongside a 2-page system description.

## Timeline (planned)

| Milestone | Date |
| --- | --- |
| NeurIPS workshop acceptance | July 11, 2026 |
| Shared task page and starter code live | Within two weeks of acceptance |
| Submissions open | Mid-August 2026 |
| Submission deadline | Late September 2026 (aligned with the paper deadline) |
| Top systems notified | Early October 2026 |
| 2-page system descriptions due | Late October 2026 |
| Results announced at workshop | December 2026 |

## Recognition

Top systems in each track present **10-minute spotlight talks** during a dedicated shared-task session at the workshop. **Best System** and **Best Student System** awards will be announced at closing. 2-page system descriptions appear on the workshop website (non-archival per NeurIPS workshop policy).

Participation does not require a paper submission to the main workshop track. Teams are welcome to submit both a shared-task entry and a paper; the two reviews are independent.

## Organizers

The shared task is co-led by members of the organizing committee with healthcare and clinical-AI backgrounds, with **Dr. Avanti Bhandarkar** (Mayo Clinic) as the primary task chair. For questions about the shared task before launch, please contact [bhandarkar.avanti@mayo.edu](mailto:bhandarkar.avanti@mayo.edu) or any of the [workshop organizers]({{ '/contact/' | relative_url }}).
