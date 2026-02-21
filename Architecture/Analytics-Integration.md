# Analytics & Consent Integration Architecture

## Overview

Designed and implemented a compliance-aware analytics infrastructure for healthcare platforms integrating Google Tag Manager (GTM), OneTrust consent management, and structured event tracking.



## Objectives

- Maintain HIPAA-aware tracking standards
- Ensure consent-based tag firing
- Standardize event tracking across locations
- Support marketing attribution and conversion analysis



## Architecture Model

### 1. Consent-Driven Tag Deployment
- GTM container gated by OneTrust consent categories
- Event triggers segmented by consent state
- Controlled activation of marketing pixels

### 2. Standardized Event Layer
Implemented structured events for:
- Form submissions
- CTA clicks
- Phone call interactions
- Blog engagement
- Referral conversions

### 3. Cross-Site Tracking Consistency
- Unified naming conventions
- Reusable GTM container logic
- Structured data layer planning



## Impact

- Enabled compliant marketing analytics
- Reduced inconsistent tracking implementations
- Improved marketing attribution clarity
- Simplified cross-site reporting



## Key Principle

Tracking should be architected, not appended.
