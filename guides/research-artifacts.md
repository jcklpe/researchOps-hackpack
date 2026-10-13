# Research Artifacts
Artifacts are the material collected or produced during a trial: notes, recordings, transcripts, responses, and other evidence. They preserve context that a report may leave out. Keep the relationship between that material and later interpretations recoverable.

## Arrange Materials Around the Work
A trial has an `artifacts/` folder. Group materials from one interview or user test under a session identifier. Surveys can hold a dataset for the collection window without creating a session for every response.

```text
my-project/
  project-brief.md
  interviews/
    trial-brief.md
    trial-plan-interview.md
    trial-report.md
    artifacts/
      session-01/
        field-notes-observer-a.md
        field-notes-observer-b.md
        transcript.txt
        recording-reference.md
  survey/
    trial-brief.md
    trial-plan-survey.md
    trial-report.md
    artifacts/
      responses-original.csv
      responses-cleaned.csv
      transformation-notes.md
```

This illustrates possible materials, not a required list. Create only what the research actually needs. Names and formats can be adapted; the links and relationships matter more than the exact spelling.

## Field Notes
Use the [field-note template](../templates/field-notes.md), an annotated trial plan, or natural notes. Keep each observer's authorship identifiable. Preserve useful raw detail rather than polishing away uncertainty or tangents. Separate what was observed, what a participant said, and what the observer inferred.

## Transcripts and Recordings
Keep transcripts connected to the source session and, where available, its recording. Mark corrections and uncertainty in machine-generated transcripts; do not treat them as perfect records. Record the source location and relevant timestamps when citing material in a report.

Materials can live in appropriate external storage. A reference in the session folder can identify the recording or transcript, its owner, version/date, access location, and relationship to the session. A link preserves a route to the source, not the source itself: check that the intended team can still retrieve it. Follow the project's consent, access, and retention arrangements. The toolkit does not impose a universal retention period.

## Survey Data
Retain the questionnaire version, collection window, and export context with the response data. Keep original exports distinguishable from cleaned or transformed datasets. Record how rows, missing answers, or exclusions were handled so a later researcher can reconstruct reported counts. The data may stay in a survey tool, spreadsheet, or other store; link that location when local copies are unsuitable.

## Other Context and Synthesis
Recruitment decisions, observer debriefs, relevant correspondence, coding notes, and synthesis materials may explain how a conclusion developed. Preserve useful context with an appropriate audience and connect reports to the evidence they use. Do not turn every private conversation into a public research artifact.

The [interview notes](../examples/community-support/interviews/artifacts/session-01/field-notes.md), [survey export](../examples/community-support/survey/artifacts/fictional-responses.csv), and [user-test notes](../examples/community-support/user-testing/artifacts/session-01/field-notes.md) illustrate different arrangements with entirely fictional material.
