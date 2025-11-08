### My Docs – Real-time Collaborative Document Editing
##### Tech Stack: Flutter, Bloc, Node.js, Express.js, Socket.IO, MongoDB, Quill
Developed a real-time collaborative document editor with live text sync, multi-user cursors, and seamless cross-device editing using Socket.IO.
Built and optimized Express.js + MongoDB APIs for scalable, low-latency collaboration, supporting multiple concurrent users with smooth performance.


##### Realtime Text Highlights & Multi-Cursor Editing

- Watch collaborators type simultaneously in realtime.  
- Each cursor and selection is color-coded for different users.  
- Text highlights update instantly as users edit the document.

![Realtime Text Highlights & Multi-Cursor Editing](./Real%20time%20highlights%20and%20mouse%20positions.png)
*Figure 1: Live editing with multiple cursors and dynamic highlights.*

##### Document Details Page (Editor with Toolbar, Collaboration, Title & Delete)

- Full rich-text toolbar: font, heading, color, bold/italic/underline, ordered/unordered lists, checkboxes, links, insert image/table, undo/redo, and more.  
- Inline **editable title** — click to rename and save.  
- Real-time collaboration: add/remove collaborators, color-coded cursors, and live edits.  

![Document Details Page — Editor](./Document%20details%20page.png)  
*Figure 2: Editor view with toolbar, inline title, collaborator avatars, and document action buttons.*

##### Document List Page (Search, Filters, Shared & Date Grouping)

- Displays a **list of all documents**, organized and grouped by dates such as **Today**, **Yesterday**, **7 Days Ago**, and exact **dates** for older documents.  
- Includes a **search bar** to quickly find documents by title.  
- Shows a **Shared Documents** section highlighting files you’ve shared or received access to.  
- Includes a **Logout option** in the toolbar/menu for quick account sign-out.  
- Clean, responsive layout that focuses on readability and easy navigation.

![Document List Page](./document%20list%20page.png)  
*Figure 3: Document list page with search, filters, shared section, and date grouping.*

##### Login & Register Page

- Provides a clean **Register** form with fields for **Name**, **Email**, and **Password** to create a new account.  
- Includes a **Login** form with **Email** and **Password** fields for existing users.  
- Both forms include validation for required fields and password strength.  
- Shows proper error messages and success notifications.  
- Smooth transition between **Login** and **Register** screens.  
- After login, users are redirected to the **Document List Page**.

![Login Page](./Login%20page.png)  
![Register Page](./register%20page.png)  
*Figure 4: User authentication screens with register and login forms.*
