# FitLens AI

## AI-Powered Creator Selection & Decision Support

FitLens AI is an evidence-grounded creator-selection copilot developed for the **NYU SPS × Google Hackathon**.

The product helps marketers move from a large creator universe to an explainable shortlist by combining campaign context, creator evidence, structured fit analysis, and human decision-making.

> **Find the shortlist. Then make the fit visible.**

**Project Type:** Hackathon Product Prototype  
**Focus:** AI Product Strategy | Creator Marketing | Decision Support  
**AI Layer:** Google AI / Gemini  
**Role of AI:** Content understanding, evidence extraction, fit reasoning, and creative translation

---

## The Problem

Creator selection can be slow, fragmented, and difficult to explain.

Marketing teams often move between creator discovery, manual content review, fit assessment, creative ideation, and internal approval using separate tools and subjective evaluation criteria.

This creates several challenges:

- High manual discovery and review effort
- Inconsistent evaluation criteria
- Scattered evidence across tools and notes
- Difficulty explaining why a creator fits a specific campaign
- Separation between creator selection and creative strategy

FitLens was designed to compress this workflow without hiding the evidence or replacing marketer judgment.

---

# Product Strategy

FitLens is structured around three decision questions:

### 1. Who should we look at?

Reduce a large creator pool through campaign-specific discovery and screening.

### 2. Why does this creator fit?

Compare **Creator DNA × Campaign DNA** to make alignment, gaps, evidence, and creative opportunities visible.

### 3. Who should we move forward with?

Compare finalists and their trade-offs while keeping the final partnership decision with the marketer.

![FitLens Product Workflow](visuals/product_workflow.png)

The goal is not to let AI choose a creator. The goal is to make a complex creator-selection decision **faster, clearer, and more explainable**.

---

# Core Product Workflow

**Campaign Context**  
↓  
**Creator Discovery & Shortlisting**  
↓  
**Campaign DNA Definition**  
↓  
**Creator DNA × Campaign DNA Analysis**  
↓  
**Evidence-Backed Fit Evaluation**  
↓  
**Creative Translation**  
↓  
**Creator Comparison**  
↓  
**Human Decision Support**

---

# Campaign DNA

Before evaluating creators, marketers define what "fit" means for the specific campaign.

FitLens allows marketers to adjust the relative importance of six evaluation dimensions rather than relying on one universal scoring model.

![Campaign DNA](visuals/campaign_dna.png)

The Campaign DNA interface includes:

- Adjustable fit weights
- Campaign DNA spider-map preview
- Transparent scoring logic
- 100% weight-balance check

This separates two concepts:

**Weight = how important the dimension is to the campaign.**  
**Score = how strongly the creator demonstrates that fit.**

This makes the evaluation criteria explicit before a creator is judged.

---

# Creator DNA × Campaign DNA

The FitLens Profile is the core product experience.

It compares what the campaign requires with what the creator's public content demonstrates.

![FitLens Profile](visuals/fitlens_profile.png)

The profile includes:

### Overall Campaign Fit
Provides a quick summary without replacing the underlying evidence.

### DNA Spider Map
Overlays Creator DNA and Campaign DNA to make alignment and gaps immediately visible.

### Fit Evaluation Summary
Explains why the creator appears compatible with the campaign and surfaces areas that may require additional review.

### Dimension Breakdown
Allows marketers to inspect individual dimensions instead of relying only on one overall score.

The question FitLens is designed to answer is:

> **How does this creator fit this specific campaign?**

---

# Evidence-Backed Analysis

FitLens is designed so that AI-generated judgments remain inspectable.

For each fit dimension, the system can connect an assessment to:

- Dimension score
- Evidence statement
- Referenced public creator content
- Specific examples or timestamps

The principle is:

> **Explainability = score + reason + inspectable evidence.**

This reduces the need for marketers to accept an unexplained AI recommendation.

---

# Creative Translation

FitLens goes beyond creator scoring by translating creator–campaign fit into a potential activation concept.

The prototype can generate:

- Suggested creative angle
- Suggested hook
- Call-to-action
- Supporting public audience-response signals

These outputs are intended as decision support and creative starting points—not automatically approved campaign concepts.

---

# Human-Centered Decision Support

The final stage brings the analysis back to the marketer.

![FitLens Decision Support](visuals/decision_support.png)

The decision layer includes:

- Human authority controls
- Candidate summaries
- Strengths and watch items
- Marketer notes
- Explicit final selection

FitLens does not autonomously approve, contact, book, or contract creators.

**AI informs the partnership decision. The marketer owns it.**

---

# How FitLens Uses AI

The prototype uses **Google AI / Gemini** as a reasoning layer.

### Inputs

- Campaign brief
- Product/category
- Campaign goal
- Target audience
- Target market
- Optional campaign requirements
- Recent public creator content
- Public metadata
- Observable content patterns
- Supporting public comment signals
- Human-entered context

### AI Reasoning

Google AI / Gemini supports:

1. **Content Understanding**  
   Identifying topics, formats, tone, and observable creator patterns.

2. **Evidence Extraction**  
   Connecting fit judgments to specific content signals.

3. **Creator × Campaign Reasoning**  
   Evaluating creators against the same Campaign DNA framework.

4. **Creative Translation**  
   Turning fit patterns into potential campaign angles, hooks, and calls-to-action.

5. **Structured Summaries**  
   Generating concise strengths, gaps, and comparison-ready explanations.

### Outputs

- Creator pool
- FitLens analysis
- Evidence-backed fit assessment
- Creator comparison
- Human decision support

---

# Responsible AI & Product Guardrails

FitLens was designed with several important limitations and guardrails.

### Audience Data
The system should not invent precise audience demographics when direct audience data is unavailable.

### Public Comments
Comment themes can provide supporting signals but should not be treated as a complete representation of a creator's audience.

### Fit ≠ Campaign Success
Fit scores describe creator–campaign alignment.

They do **not** predict:

- Views
- Sales
- Conversions
- ROI

### Evidence Freshness
Creator content changes over time, so recent-content weighting and timestamps matter.

### Human Commercial Context
Factors such as fees, negotiation, relationship history, exclusivity, and approvals remain human inputs.

---

# Prototype Validation

Rather than claiming untested campaign-success improvements, the prototype proposes measurable validation criteria.

### Efficiency
- Time to qualified shortlist
- Time to review one creator

### Quality
- Evidence traceability
- Human reviewer agreement

### Usability
- Decision clarity

A proposed validation test would give marketers the same campaign and creator set **with and without FitLens**, then compare review time, evidence quality, and decision confidence.

The success criterion is:

> **Faster review + more inspectable reasoning + clearer trade-offs, while the final partnership decision remains human.**

---

# Business Model & Scale

The product concept also explores two potential usage levels:

### FitLens Starter
Designed for individual marketers and smaller campaigns with access to the core creator-analysis workflow.

### FitLens Pro
Designed for brands, agencies, and larger creator programs requiring broader discovery, more creator analysis, additional saved campaigns, and greater comparison capacity.

The proposed paid model expands workflow capacity rather than changing the quality of the underlying FitLens analysis.

---

# Full Product Walkthrough

📄 [View the Complete FitLens AI Product Walkthrough](presentation/FitLens_AI_Product_Walkthrough.pdf)

---

# Skills Demonstrated

`AI Product Strategy` `Product Design` `Business Analysis` `Creator Marketing` `Decision Support` `Human-Centered AI` `Responsible AI` `Product Prototyping` `Explainable AI` `Google AI` `Gemini`
