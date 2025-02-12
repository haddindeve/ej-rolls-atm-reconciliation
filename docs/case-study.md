# ATM Electronic Journal Parser and GL Reconciliation - case study

**Engineer:** Muhammad Tanveer - Full-Stack AI Automation Engineer  
**Repository:** https://github.com/haddindeve/ej-rolls-atm-reconciliation

## Context

Reconciling ATM activity means reading electronic journal logs - unstructured, machine-specific text - and matching them by hand against general ledger entries. It is slow, and the errors it produces are financial ones.

## What I built

A parser that turns raw EJ text into structured transaction records, then a reconciliation stage that matches those records against GL statements and reports what does not agree. The parser is tolerant of the format variation that makes these logs awkward to process.

## Capabilities delivered

- Electronic journal parsing
- Format-variation tolerance
- Automated GL matching
- Discrepancy reporting

## Outcome

- Manual log reading replaced by structured extraction
- Discrepancies surfaced as exceptions rather than found by inspection

## Source

The implementation is held in a private repository. Access can be arranged on request - [mtanveertahir66@gmail.com](mailto:mtanveertahir66@gmail.com) or [LinkedIn](https://www.linkedin.com/in/muhammad-tanveer-advenno/).