Purpose:
To prepare clear annotation rules and confirm annotator readiness before execution starts.

Scope:
In: Label rules definition, edge case documentation, training readiness  
Out: Actual annotation execution

Who runs this:
Annotation Lead / Intern

Inputs needed:
- Project requirements
- Sample images (toy dataset)
- Tool decision already finalized

Outputs produced:
- Label specification document
- Edge case library
- Training quiz for annotators

Tools touched:
- Documentation only (no annotation tool actions)

Timebox range + drivers:
45–60 minutes.
Time may increase if label rules are unclear or many edge cases are found.

Failure modes:
- Label definitions are vague
- Edge cases are not documented
- Training readiness not checked
- Conflicting rules across documents
- Assumptions not written down

Escalation rules:
- If label rules cannot be clearly defined, pause and escalate to project lead.
- If edge cases keep repeating, stop and update the spec.

Assumption ledger:
- Project is a toy project with sample data
- Labels are limited and already known

Step-by-step procedure:
1. Review project goal → understand what needs to be labeled.
2. Define each label clearly in the label spec → include what to label and what not to label.
3. Review sample images → identify confusing cases.
4. Document edge cases with clear decisions.
5. Create a short training quiz → test annotator understanding.
6. Review all planning documents once → ensure consistency.

Quality checks inside the flow:
- Each label has clear do and do-not rules.
- Edge cases have a decision written.
- Training quiz has pass criteria defined.

Artifacts produced:
- TPL_Label_Spec_v0.1.md
- TPL_EdgeCase_Library_v0.1.md
- TPL_Training_Quiz_v0.1.md

Example run:
- Defined rules for Person, Car, and Dog labels.
- Documented partial visibility and background object cases.
- Created a 4-question training quiz.

Acceptance criteria:
- A new annotator can read the documents and start work without asking questions.
- At least one example and one failure case are documented.
