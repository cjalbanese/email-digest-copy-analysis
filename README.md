# Email Digest Copy Analysis

Analysis of 379 survey digest emails to optimize clicks-to-kicks ratio through subject line and preheader testing.

## Key Findings

### Biggest Opportunities (Positive Impact)
- **Metabolic topics:** +109% improvement (p<0.001)
- **Ampersands (&):** +103% improvement (p<0.001)

### Biggest Problems (Negative Impact)
- **"Cancer" word:** -47% impact (p=0.004)
- **"Treatment" word:** -40% impact (p<0.001)
- **"Closing Soon":** -29% impact (p=0.015)
- **Colons in subject:** -30% impact (p=0.011)

## Files

- **[email_digest_copy_analysis.md](email_digest_copy_analysis.md)** - Complete analysis with examples, recommendations, and implementation guide
- **[truncation_analysis.md](truncation_analysis.md)** - Analysis of whether "and Other Survey Opportunities" visibility affects performance
- **digest_copy_visualizations.png** - Visual analysis charts for main copy analysis
- **truncation_analysis.png** - Visual analysis charts for truncation study

## Quick Start

### Immediate Actions (This Week)
1. Remove "Closing Soon" from all subjects (+29% improvement)
2. Replace "Treatment" with "Medications for" / "Managing" (+40% improvement)
3. Add "&" between main topics (+103% improvement)
4. Replace "cancer" with "oncology" (+47% improvement)

### Expected Impact
Combined improvements could boost median clicks-to-kicks from **13.5 to 25-35 range** (100-150% improvement).

## Dataset
- **Total emails:** 5,825
- **Survey digests analyzed:** 379 (with measurable kicks)
- **Current median C2K:** 13.5
- **Features analyzed:** 43 copy-related elements

## Methodology
- T-tests for binary features
- Correlation analysis for numeric features
- Random Forest feature importance
- Word frequency analysis (high vs low performers)

## Real Examples Included

The full analysis includes:
- Top 10 highest performing subjects (C2K: 102-215)
- Bottom 10 lowest performing subjects (C2K: 1.0)
- Before/after copy rewrites
- 5+ ready-to-use templates
- A/B testing framework

## Analysis Date
February 5, 2026

---

**View the full analysis:** [email_digest_copy_analysis.md](email_digest_copy_analysis.md)
