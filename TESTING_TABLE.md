# Testing Table — EduTrack Student Portal

| TC ID | Module | Test Input / Action | Expected Result | Status |
|---|---|---|---|---|
| TC01 | Navigation | Click Dashboard | Dashboard page opens | Pass |
| TC02 | Navigation | Click Courses | Courses page opens | Pass |
| TC03 | Navigation | Click Attendance | Attendance details display | Pass |
| TC04 | Navigation | Click Assignments | Assignment list displays | Pass |
| TC05 | Navigation | Click Timetable | Weekly timetable displays | Pass |
| TC06 | Navigation | Click Notices | Notices page displays | Pass |
| TC07 | Navigation | Click Profile | Student profile displays | Pass |
| TC08 | Course Filter | Select “AI & Data Science” | Only AI & DS courses display | Pass |
| TC09 | Course Filter | Select “Core” | Only core courses display | Pass |
| TC10 | Assignment Validation | Add assignment with empty fields | Validation message appears | Pass |
| TC11 | Add Assignment | Enter name and date, click Save | New assignment appears | Pass |
| TC12 | Assignment Submit | Click Submit | Status changes to Submitted | Pass |
| TC13 | Assignment Filter | Click Pending | Pending assignments display | Pass |
| TC14 | Assignment Filter | Click Submitted | Submitted assignments display | Pass |
| TC15 | Notice Search | Enter “exam” | Matching notice displays | Pass |
| TC16 | Global Search | Enter a keyword and press Enter | Relevant portal page opens | Pass |
| TC17 | Dark Mode | Click theme button | Dark theme toggles | Pass |
| TC18 | Profile | Click Edit Profile and enter a name | Profile name updates | Pass |
| TC19 | Responsive UI | Open at tablet width | Layout adapts without major overflow | Pass |
| TC20 | Responsive UI | Open at mobile width | Single-column layout and mobile navigation work | Pass |
| TC21 | Data Integrity | Refresh after normal browsing | Static demo data remains available | Pass |
| TC22 | Usability | Use sidebar navigation repeatedly | User can move between modules easily | Pass |

## Testing Method
- Functional testing: checked each button and interactive module.
- UI testing: checked spacing, cards, forms and tables.
- Responsive testing: checked desktop, tablet and mobile layouts.
- Validation testing: tested empty assignment fields.
- User-flow testing: opened dashboard → assignments → added task → submitted task.
