Problem Statement
Employee “S” nominated herself for the XYZ training program scheduled for October. Upon nomination, she received a notification indicating that the batch was already full and that Skillverse would inform her if any seats became available. As a precaution, she also submitted her nomination for the November batch and continued monitoring training-related notifications through the Skillverse portal.
Due to high demand, the HR team opened additional training sessions, and S received an invitation to attend an earlier session in September, delivered by a third party training vendor. She accepted the invitation and successfully completed the two day session.
However, Skillverse continued sending her invitations for the October and November batches. Since she had already completed the training, she did not attend these additional sessions. After the November batch, Skillverse issued a notification restricting her from nominating for any further trainings for the next six months, citing her “non attendance” for the XYZ sessions she had originally nominated for.
Root Cause
Although the third party vendor’s attendance data was imported into the HR Suite, this information was not synchronized with the Skillverse portal. As a result, Skillverse did not register S’s completed training and incorrectly applied the non attendance penalty.
Proposed Solution
Attendance records imported from third party vendors into the HR Suite must be automatically synchronized with the Skillverse portal to ensure accurate completion status and prevent incorrect nomination restrictions.
Additional Improvements
1.	Auto revocation for exited employees
o	If an employee has left the organization, any pending training nominations should be automatically revoked.
o	Released seats should be reassigned to eligible employees in the waiting queue.
2.	Quarterly training demand survey
o	Conduct a quarterly survey inviting employees to recommend training programs, including those not currently available in Skillverse.
o	Courses receiving the highest number of recommendations may be reviewed for inclusion on the platform.
3.	Certificate upload and expiry tracking
o	Introduce a feature allowing employees to upload completion certificates.
o	Skillverse should notify employees when a certificate is nearing or has passed its expiry date.
4.	Next level certification notifications
o	If an employee completes an entry level or foundation certification, Skillverse should automatically notify them about the next level available in the certification pathway.



















Our solution is built using IBM Watsonx AI combined with Python, enabling us to create an intelligent automation layer that eliminates errors caused by manual updates and ensures real time synchronization across systems. Watsonx serves as the AI engine powering automated decision making, data interpretation, and workflow optimization, while Python functions as the core development language that structures the Skillverse logic, manages employee data, processes training records, and interacts with HR Suite.
This AI assisted design allows us to:
•	Automatically detect and reconcile mismatches between HR Suite and Skillverse
•	Reduce operational delays and human errors
•	Provide timely insights, alerts, and recommendations for employees and HR
•	Maintain accurate attendance and certification records across the organization
•	1. Data Intake & Understanding (Watsonx + Python)
•	Watsonx AI reads training nominations, attendance information, and employee status updates. Python organizes this information using structured classes such as Employee, Training, and Skillverse, ensuring a consistent and robust data model.
2. Real Time Synchronization
Watsonx AI continuously monitors data updates across systems.
When the HR Suite imports attendance data from a third party vendor, Python triggers automated synchronization so that the Skillverse portal is instantly updated.
This prevents issues such as incorrect training restrictions or duplicate batch invitations.
3. Automated Error Prevention
The AI system identifies anomalies such as:
•	Employees flagged absent despite completing vendor led sessions
•	Nominations that remain active even after an employee has exited
•	Certificates that have expired and require renewal
•	Employees eligible for next level certifications
These checks help ensure data integrity and reduce manual correction efforts.
4. Smart Notifications & Recommendations
Watsonx generates intelligent alerts, including:
•	Certificate expiry reminders
•	Next level certification suggestions
•	Available seat notifications
•	Training recommendations based on popularity, interest patterns, or organizational needs
5. Continuous Improvement & Learning
AI evaluates past training trends, employee participation patterns, and feedback.
It supports quarterly training demand surveys and identifies high value programs that can be added to Skillverse to improve employee development and align with business goals.
Additional Enhancements Enabled by Watsonx AI
✔ Auto revocation of nominations for exited employees ensures efficient seat management and automatic reallocation to employees in the queue.
✔ Quarterly AI supported survey analysis helps identify in demand courses with high organizational relevance.
✔ Certificate upload & expiry tracking allows employees to upload certifications while the system sends proactive renewal reminders.
✔ Next level certification guidance helps employees progress through structured learning paths after completing foundation level courses








