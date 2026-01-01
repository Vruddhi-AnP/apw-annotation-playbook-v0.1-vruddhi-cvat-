Purpose:
To create a toy annotation project and task in CVAT using sample images.

Scope:
In: Project creation, label setup, task creation, image upload  
Out: Full annotation execution and quality review

Owner role:
Annotation Operator / Intern

Inputs needed:
- CVAT cloud access
- Public sample image dataset (10 images)
- Project naming and label list

Outputs produced:
- CVAT Project with defined labels
- CVAT Task with uploaded images
- Initial task export (ZIP)

Tools touched:
- CVAT (Cloud version)

Timebox range + drivers:
30–45 minutes.
Time may increase if image upload is slow or labels need correction.

Failure modes:
- Labels created with wrong shape type
- Task created outside the intended project
- Images fail to upload
- Incorrect dataset selected
- Export file not generated

Escalation rules:
- If images fail to upload after retry, stop and inform the project lead.
- If labels are wrongly configured after task creation, pause before annotation.

Assumption ledger:
- Using CVAT cloud version
- Dataset is public and non-client
- Default CVAT task settings are sufficient for toy project

Step-by-step procedure:
1. Open CVAT and go to Projects tab → Project list is visible.
2. Create a new project and add rectangle labels (Person, Car, Dog) → Project is saved.
3. Open the project and create a new task → Task creation form loads.
4. Upload 10 sample images → All images are listed successfully.
5. Submit task with default settings → Task is created under the project.
6. Open the task and annotate one sample box → Annotation saves successfully.
7. Export the task data as ZIP → Export file is downloaded.

Embedded quality checks:
- Total labels = 3 and all are rectangle type.
- Image count in task = 10.
- Task appears under correct project.
- Export ZIP file is generated successfully.

Artifacts produced:
- CVAT project and task (tool state)
- Task export ZIP file
- Screenshots stored in EVID__/

Example run on 10 items:
- Created project with 3 labels.
- Uploaded 10 public images.
- Annotated 1 image for smoke testing.
- Exported task as ZIP.

One failure-case walkthrough:
- Issue: Images upload partially.
- Detection: Image count less than expected.
- Action: Delete task and recreate task with correct image selection.
