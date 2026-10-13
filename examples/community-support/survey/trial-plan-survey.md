**Fictional worked example. All participants, activities, and results are invented.**

**Blank source:** [Template](../../../templates/trial-plan-survey.md)

# Trial Plan: Survey
**Trial:** [Trial brief](trial-brief.md)
**Questionnaire version:** Fictional v1, shown below
**Collection owner:** Example researcher

## Introduction
This fictional questionnaire asks about finding the community center. A real introduction would explain purpose, participation choices, use of responses, duration, and contact arrangements before distribution.

## Questionnaire
1. Which route did you first use to contact the community center? Select one: website; telephone; walk-in; another route; prefer not to answer. Export column: `first_route`.
2. Before making contact, did you know what would happen next? Select one: yes; no; not sure; prefer not to answer. Export column: `next_step_clear`.

Both items are optional in this illustration. `response_id` is an invented row identifier, not a question or contact detail.

## Review and Pilot
The example team would check that “first contact” is understood consistently and that options cover likely routes. Record changes before distribution. No actual pilot occurred.

## Distribution and Response Window
Illustrative channel: invitation at reception, open for seven days, with no reminder. This reaches current visitors and does not cover people unable to access the center.

## Collection and Export
[fictional-responses.csv](artifacts/fictional-responses.csv) contains six invented complete responses. There are no missing values, exclusions, or duplicates in this teaching dataset. In real work, preserve the original export and document any transformations separately.

## Analysis Plan
Count the routes and clarity answers within these six rows. Use six as each denominator here; distinguish “not sure” from “no.” Do not infer population proportions from this example.
