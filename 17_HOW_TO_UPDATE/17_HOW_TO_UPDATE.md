# How to Update — STORYBOOK

**Project:** `STORYBOOK`
**Category:** DESIGN_TOOLS
**Domain:** design tools and creative software
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
STORYBOOK --version
STORYBOOK check-update
```

### Applying Updates
```bash
pip install --upgrade STORYBOOK
```

### Rolling Back
```bash
pip install STORYBOOK==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
