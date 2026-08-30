# CV project

Source repository for CV versions, job ads, motivational/application letters, and evidence used to assess candidate/job fit.

## Structure

```text
cv/
  Historical and role-tailored CV versions
ads/
  Captured job advertisements
letters/
  Motivational and application letters
assessment/
  Evidence, current context, screening criteria, and conflict-resolution guidance
```

## AI usage rules

1. **Do not invent missing facts.** If an employer name, date, metric, title, or requirement is absent, mark it unknown.
2. **Preserve provenance.** Converted source files include the original Word filename and SHA-256 hash.
3. **Do not silently merge conflicts.** Read `assessment/source-conflicts.md` before generating a new CV or fit assessment.
4. **Prefer current confirmed context.** `assessment/current-profile.md` contains newer project facts that may post-date historical CVs.
5. **Ground tailoring in the job ad.** Save the ad under `ads/` before producing a tailored CV/letter when possible.
6. **Keep claims evidence-backed.** Use the strongest relevant achievements from CV and assessment sources; do not create metrics.
7. **Keep historical artifacts historical.** Generate new tailored documents as new files rather than rewriting source conversions.

## Migration status

All 12 Word documents attached to the ChatGPT CV project were converted to Markdown. Two mixed documents containing both a letter and CV were split into their logical artifacts while retaining their source provenance.

This repository is hosted as `gastik/my-cv`. The project content was migrated from the ChatGPT CV project on 2026-08-30.
