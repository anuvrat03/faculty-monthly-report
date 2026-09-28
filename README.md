# Faculty Monthly Report Submission System

A simple, lightweight web application that allows faculty members to submit their monthly academic and operational reports along with supporting documents (PDF, Word, Images). 

The app uses **GitHub Pages** for the user interface, **Google Apps Script** as the backend service, and **Google Sheets / Google Drive** for secure data storage.

---

## 🌟 Key Features

* **No Code/Low Code Stack:** Easy to maintain without complex server management.
* **Automated Data Sorting:** Faculty submissions automatically align into designated columns in Google Sheets.
* **Document Attachment:** Files uploaded by faculty are stored directly in a designated Google Drive folder.
* **View-Only Admin Access:** Admins can view submitted reports and download files without having permission to edit original submissions.
* **Mobile Friendly:** Works seamlessly on smartphones, tablets, and desktops.

---

## 🛠️ Tech Stack & Architecture

1. **Frontend:** HTML5, CSS3, JavaScript (Hosted via GitHub Pages)
2. **Backend API:** Google Apps Script Web App
3. **Database:** Google Sheets
4. **File Storage:** Google Drive

---

## 📊 Google Sheet Column Layout

Submissions are automatically logged with the following structure:

| Column | Field Name | Description |
| :--- | :--- | :--- |
| **A** | `Timestamp` | Submission date and time |
| **B** | `Faculty Name` | Name of the faculty member |
| **C** | `Department` | Academic department |
| **D** | `Reporting Month` | Month and year of the report |
| **E** | `Report Summary` | Summary of work done |
| **F** | `File Link` | Direct link to uploaded Google Drive file |

---

## 👥 How to Use

### For Faculty
1. Open the published GitHub Pages web link.
2. Fill in your name, department, reporting month, and work summary.
3. Attach an optional supporting document (PDF/Word/Image).
4. Tap **Submit Report**.

### For Administrators
1. Open the shared Google Sheet (set to **Viewer** mode).
2. View all submitted data organised by date and time.
3. Click the links in **Column F** to open attached documents in Google Drive.
