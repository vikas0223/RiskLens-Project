# RiskLens - Adaptive Risk Monitoring Platform

**Project 1A | RiskLens Technologies**  
Prepared for Zetheta Algorithms Private Limited  
Design Source: [RiskLens Figma File](https://www.figma.com/design/xDDU1m6ZtyvMkoeFlhv4wh)

---

## 📌 Overview

This repository contains the core design specifications, audits, tokens, and verification logs for **RiskLens**, an enterprise adaptive risk monitoring platform tailored for multi-asset portfolio risk analytics across four primary roles:
- **Junior Risk Analyst** (verification, guided anomalies)
- **Senior Portfolio Manager** (investigation, fast comparisons, direct drill-downs)
- **Chief Risk Officer** (firm-wide posture, executive summary, presentation-ready reporting)
- **Compliance Officer** (auditability, breach timeline, evidence, mandatory comments)

---

## 📁 Repository Contents

| File | Description |
| :--- | :--- |
| [`Design_Specification.pdf`](./Design_Specification.pdf) | Comprehensive engineering handoff specification (v2.1) covering design tokens, typography, component API contracts, responsive behavior (Desktop 1440×900, Tablet 768×1024, Mobile 375×812), financial visualizations (VaR, CVaR, Greeks, Drawdown, Stress Testing), and core prototype interaction flows. |
| [`Accessibility_Audit_Report.pdf`](./Accessibility_Audit_Report.pdf) | Formal WCAG 2.1 AA accessibility audit report (v1.1) evaluating 48 responsive frames, contrast ratios, keyboard navigation order, screen-reader announcement scripts, and the P0–P2 remediation plan. |
| [`Competitive_Audit_Report.pdf`](./Competitive_Audit_Report.pdf) | Public-source competitive audit (v1.0) reviewing Bloomberg PORT, MSCI RiskMetrics RiskManager, and Axioma Risk / Portfolio Analytics with a feature matrix and reusable UX pattern library. |
| [`Error_Identification_Log.pdf`](./Error_Identification_Log.pdf) | Comprehensive review and correction log (v2.1) of all 13 deliberate errors embedded in the training material with citations and RiskLens architectural notes. |
| [`tokens.json`](./tokens.json) | Exported semantic design tokens from Figma local variables and styles (color palette, spacing scale, control sizes, border radii, breakpoints, typography, and focus ring definitions). |

---

## 🎨 Design System Summary

- **Theme**: Dark Institutional Financial Workspace
- **Background**: `#0B0F14`
- **Surface**: `#111820`
- **Surface Elevated**: `#17212C`
- **Border**: `#2A3644`
- **Accent**: `#3DD6E8` (Cyan)
- **Status Semantics**: Success (`#43D17A`), Warning (`#F2B84B`), Critical (`#FF5C6C`)
- **Typography**: Inter (Display, Heading, Section, Body, Caption)
- **Base Rhythm**: 8px grid (with 4px micro-spacing)
- **Primary Touch Target**: 44px
