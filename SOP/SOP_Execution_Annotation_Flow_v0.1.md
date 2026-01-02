Purpose:
To run annotation work in a controlled and repeatable way.

Scope:
In: Batch creation, annotation, review, rework
Out: Final delivery and closure

Who runs this:
Annotation Intern / Reviewer

Inputs needed:
- Approved label spec
- Approved edge case library
- Trained annotators

Outputs produced:
- Annotated data
- Daily production report

Tools touched:
- Annotation tool (CVAT)

Timebox:
Depends on batch size and complexity.

Failure modes:
- Annotators skip rules
- Low quality annotations
- Review not performed
- Rework not tracked
- Progress not reported

Escalation rules:
- If quality is consistently poor, pause the batch and inform the lead.
- If blockers appear, stop work and escalate.

Assumption ledger:
- Annotators have passed training quiz.

Step-by-step procedure:
1. Split data into small batches → batches are manageable.
2. Assign batch to annotator → ownership is clear.
3. Annotator completes annotation → follows label spec.
4. Reviewer checks annotations → issues are flagged.
5. Annotator fixes issues → rework completed.
6. Update daily report → progress is visible.

Quality checks:
- Reviewer checks each batch before acceptance.
- Rework is completed before moving forward.

Artifacts produced:
- TPL_Batch_Plan_v0.1.md
- TPL_Daily_Production_Report_v0.1.md

Example run:
- One batch of images annotated, reviewed, and corrected.
