
https://entnt-assignment-peach.vercel.app/


Application Functionality


Admin Module: Allows admins to set up companies. Admins can configure communication parameters such as frequency and method. Admins have tools for managing data related to companies and communication tasks.

User Module: Users can visualize, manage, and log communication tasks. Provides two views: Past Communications: Displays all completed communications sorted by date. Upcoming Communications: Lists all planned communications that are scheduled for future dates.

Includes a Notification System: Overdue communications are flagged. Communications due today are highlighted. Users can log communication events through a dedicated form.

Communication Logging: Supports logging communication for single or multiple companies at once. Includes fields for date, method, and optional notes. Automatically associates logged communications with the selected companies.

Dark Mode Support: Enhanced user interface for dark mode compatibility. Ensures proper contrast and visibility of all form elements. Dynamic Filtering and Sorting:

Filters communications based on time (past vs. upcoming). Sorts communications in descending order for past and ascending for upcoming tasks.

Known Limitations:
Notification Accuracy: The notification system relies on computed properties from data. If there are data inaccuracies (e.g., missing periodicity or incorrect communication logs), the notifications might not reflect the correct status.

Limited Admin/User Separation: Current implementation does not differentiate between admin and user modes at the authentication level. Both admin and user functionalities are accessible within the same UI, separated by tabs or sections. Future implementations might require proper role-based access control.

Limited Data Validation: Dependencies between communication methods, companies, and communications are not strictly enforced. Deleting a company or communication method could leave orphaned records.
