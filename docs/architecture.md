# ATM Electronic Journal Parser and GL Reconciliation - architecture

A parser that turns raw EJ text into structured transaction records, then a reconciliation stage that matches those records against GL statements and reports what does not agree. The parser is tolerant of the format variation that makes these logs awkward to process.

## Components

### EJ parser

Raw journal text to structured transactions

### Normalisation

Handling of machine and format variation

### Reconciliation

Matching against general ledger entries

### Reporting

Exception and discrepancy output

## Stack

| Layer | Technology |
| --- | --- |
| Language | Python |
| Parsing | Tolerant text parsing of EJ formats |
| Output | Structured reconciliation reports |

Designed and implemented by Muhammad Tanveer - Full-Stack AI Automation Engineer.