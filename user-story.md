**Title**: Track Interviewees and Their Progress

**As a** Hiring Manager

**I want** to track interviewees and their progress through the hiring process

**So that** I can efficiently manage candidates, monitor their status, and make informed hiring decisions.

**Business Logic**:
- Each interviewee should be associated with a specific job posting.
- The system should track the stage of the hiring process for each interviewee (e.g., Applied, Phone Screen, First Interview, Second Interview, Offer, Hired, Rejected).
- Hiring managers should be able to add notes to each interviewee's profile.
- The system should allow for filtering and sorting of interviewees based on various criteria (e.g., job posting, interview stage, date applied).

**Acceptance Criteria**:
1. The system allows me to add a new interviewee and associate them with a specific job posting.
2. The system allows me to update an interviewee's status within the hiring process.
3. The system allows me to view a list of all interviewees for a specific job posting, filtered by their current status.
4. The system allows me to add and view notes for each interviewee.
5. The system allows me to sort interviewees by various criteria, such as name, application date, or interview stage.

**Functional Requirements**:
- Add Interviewee:  Input fields for name, contact information, resume, and job posting.
- Update Interviewee Status:  Dropdown menu to select the current stage of the hiring process.
- View Interviewee List:  Display a list of interviewees with sortable columns for name, job posting, status, and application date.  Filtering options based on status and job posting.
- Add/View Notes:  Text area for adding notes, with a timestamp for each note.
- Search/Filter Interviewees: Functionality to search by name or filter by status and job posting.

**Non-Functional Requirements**:
- Performance: The system should load and respond quickly, even with a large number of interviewees.
- Security:  Access to interviewee data should be restricted based on user roles and permissions.
- Usability: The system should be intuitive and easy to use.
- Accessibility: The system should be accessible to users with disabilities.

**UI Design**:
- A dashboard view showing an overview of all active job postings and the number of interviewees at each stage.
- A detailed view for each interviewee, showing their contact information, resume, interview history, and notes.
- Clear and concise labeling of all fields and buttons.
- Use of color-coding to visually represent the different stages of the hiring process.
- Responsive design to ensure usability on different devices.
