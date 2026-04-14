# 🟣 FHC Intake Training — Interactive HINC Guide

**Flemingdon Health Centre | East & North Toronto | January 2026**

An interactive, self-paced web training tool for Intake Staff, HINCs (Health Intake Navigation Counsellors), and Medical Secretaries. Built from the FHC Intake Process Training curriculum.

---

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to **Settings → Pages → Deploy from branch → main / root**
3. Share the URL with your team: `https://[your-org].github.io/fhc-intake-training`

### Option 2: Run Locally
```bash
# No build step needed — pure HTML/CSS/JS
# Just open index.html in any browser:
open index.html
```

---

## 📚 What's Included

| Module | Description |
|--------|-------------|
| 🎯 Why This Matters | Provincial target, FHC's goal, the 5 key messages |
| 🏗️ The 5-Component System | Referral funnel, Purple Tracker, Triage, Stages, Equity Lens |
| 🗺️ Patient Journey | Stages 0 → 3 explained with roles and metrics |
| ⚙️ Intake Workflow | Step-by-step process (varies by site) |
| 👥 Roles & Responsibilities | Med Sec vs. HINC responsibilities |
| 🚦 Triage Codes | Red / Yellow / Green decision guide |
| 🟣 The Purple Tracker | How to add, fill, and update — the golden rule |
| 📋 All 17 Statuses | Complete reference with definitions |
| 📞 HCC & Call Scripts | Workflow + sample call scripts with post-call actions |
| 🪪 Insurance Status | CHCR, IFH, uninsured — where to document |
| ❓ FAQs | Common patient questions + Access Clinic hours |
| 🔧 Triage Decision Tool | **Interactive** — enter patient details, get a code |
| 🎮 Tracker Simulator | **Interactive** — practice updating the tracker |
| 🎭 Scenario Exercises | **Interactive** — 4 real-world scenarios |
| ✅ Knowledge Check | **Interactive** — 10-question quiz with instant feedback |

---

## 🛠️ Customisation

All content is in a single file (`index.html`) for easy maintenance:

- **Update content**: Search for the module ID (e.g., `mod-tracker`) and edit the HTML directly
- **Add scenarios**: Extend the `scenarioAnswers` object in the `<script>` section
- **Add quiz questions**: Add objects to the `questions` array
- **Change colours**: Edit CSS variables at the top of `<style>` (`:root { ... }`)
- **Add new modules**: Add to `moduleOrder` array, create a `div#mod-[name]`, and add a nav link

---

## 📋 Content Source

Based on the **FHC Intake Process Training Guide (January 2026)**. For the authoritative reference, see the **FHC Attachment Manual (January 2026)**.

Questions? Contact your intake lead.

---

## 🔒 Privacy Note

This tool contains **no patient data**. All scenarios use fictional patient names. The tool runs entirely in the browser — no data is sent to any server.

---

*Flemingdon Health Centre · For internal training use only*
