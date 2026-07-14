# HRIS-Driven Identity Lifecycle — Reference Site

A single-page reference architecture and runbook documenting a complete HRIS-driven identity lifecycle pipeline: **Paylocity (HR system of record) → Okta (identity platform) → downstream SaaS apps** (Google Workspace, Atlassian, Zscaler, 1Password via a GCP-hosted SCIM bridge), with Jamf handling devices alongside.

It covers five phases — Discovery & Audit, Legacy Reconciliation, Joiner, Mover, and Leaver — plus a cross-cutting Safety Model, a glossary, and sources. Written for engineers coming from Entra ID: every identity term is defined inline the first time it appears.

**Live site:** https://dumont94.github.io/TestIAM-pipeline-oktav2/

This is a static, single-file site (`index.html` with all CSS and JS inline). There is nothing to install, build, or configure — clone it and open the file, or serve it from GitHub Pages.
