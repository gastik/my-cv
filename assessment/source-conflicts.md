---
type: assessment_guidance
person: Igor Popov
source: "comparison of migrated CV documents"
status: "derived; requires user confirmation before treating conflicts as resolved"
---

# Source conflicts and evidence rules

Historical CVs are retained as evidence, not as a single reconciled truth. Future AI work must not silently choose between conflicting claims.

## Known conflicts to resolve when material

- **Wingback title:** historical versions use Product Owner, Chief Product Owner, and Product Owner / Interim CTO.
- **Barclays title:** versions include Team Lead, Vice President of Engineering, and Head of Asset Inventory and Discovery / combinations of these titles.
- **Latest chronology:** several historical CVs show Wingback as present, while newer project context adds a Senior Data Engineer role for 2024–2026.
- **BS/2 dates:** at least one historical source contains an impossible/reversed date range (`2020.10 – 2020.02`), while newer versions show October 2020–February 2021.
- **Scale metrics:** historical documents mention multiple data volumes (for example, 4 TB/week and ~2.5 TB/day) in different contexts. Keep the metric tied to its original source/context unless verified.
- **Technology claims:** some application letters mention Google Cloud, AWS, .NET, Delphi, Python and broad DevOps/microservice migration experience; later CV variants emphasize different stacks. Do not assume every technology was used in every role.

## Evidence hierarchy

1. Explicitly user-confirmed current project context.
2. Role-specific achievements in `assessment/`.
3. Newer CV variants in `cv/`.
4. Older CV variants and application letters.
5. Inference only when clearly labeled as inference.

When a job application depends on a disputed title, date, metric, employer, or technology, flag it rather than inventing a reconciliation.
