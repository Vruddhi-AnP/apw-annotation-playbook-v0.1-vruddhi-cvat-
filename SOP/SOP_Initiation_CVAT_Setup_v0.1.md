Purpose:
To set up access to CVAT and confirm the tool is ready for running a toy annotation project.

Scope:
In: CVAT account access and basic navigation check  
Out: Project creation and annotation work

Owner role:
Annotation Operator / Intern

Inputs needed:
- Internet connection
- CVAT cloud access
- Laptop with modern browser

Outputs produced:
- Verified CVAT login
- Confirmation that tool is accessible and usable

Tools touched:
- CVAT (Cloud version)

Timebox range + drivers:
10–15 minutes.
Time may increase if login issues or network problems occur.

Failure modes:
- Unable to log in due to wrong credentials
- CVAT dashboard not loading
- Browser compatibility issues
- Session timeout
- Organization not visible after login

Escalation rules:
- If login fails more than 2 times, stop and inform the project lead.
- If dashboard does not load after refresh, pause work and report.

Assumption ledger:
- Using CVAT cloud, not self-hosted
- User has valid login credentials provided earlier

Step-by-step procedure:
1. Open CVAT cloud URL in browser → Login page loads.
2. Enter email and password → User is logged in successfully.
3. Verify dashboard is visible → Projects and Tasks tabs are accessible.
4. Click between tabs to confirm navigation works → No errors observed.

Embedded quality checks:
- Login successful without errors.
- Dashboard loads within reasonable time (<10 seconds).
- Main navigation tabs are clickable.

Artifacts produced:
- Screenshot of CVAT dashboard after login (stored in EVID__/)

Example run on 10 items:
- Not applicable at this stage as no data is handled.

One failure-case walkthrough:
- Issue: Dashboard not loading after login.
- Detection: Blank screen or continuous loading.
- Action: Refresh browser once. If still not working, log out and retry. If issue persists, escalate.

