

**Date:** 05/06/2026
**Status:** #in-progress
**GitHub:** [link](https://github.com/gotbyrd-sudo/fedramp-checklist)

## What this prototype demonstrates
Demonstrates a web-based implementation tracker for the FedRAMP High baseline (NIST SP 800-53 Rev 5). Teams can mark controls complete, see progress by control family, and filter down to outstanding items.

**Intended audience:** Cloud service providers preparing a FedRAMP High authorization package for a federal agency operating at IL4/IL5.

- 58 controls across 12 NIST 800-53 families (AC, AU, CM, CP, IA, IR, MA, PE, RA, SA, SC, SI)
- Per-control completion tracking with timestamp and actor recorded
- Summary view: overall progress + per-family breakdown
- Search and "incomplete only" filter

## Prompt used
Create a FastAPI app that serves a FedRAMP High control checklist. Controls should be stored as JSON, with endpoints to list all controls, mark a control complete, and return a completion summary. Include a basic React frontend that renders the checklist with checkboxes. Use synthetic but realistic federal control data.

## What worked
Prototype successfully ran from a single prompt

## What didn't


## Next iteration ideas


## Links
- Related PRD: 
- Related work target: