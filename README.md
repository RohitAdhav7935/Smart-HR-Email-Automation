# 📧 Smart HR Email Automation & CV Management System

## 📌 Overview

The **Smart HR Email Automation & CV Management System** automates job application emails and tracks application activity through a custom dashboard.

This project uses Google Forms, Google Sheets, Google Drive, Gmail, and Google Apps Script to simplify the job application process, automate email delivery, and maintain application history in one place.

## 🚀 Live Project Links

* 📝 **Job Application Form:** [Open Google Form](https://docs.google.com/forms/d/e/1FAIpQLSetYCa62oXrViyR3e1aHHl196XILTRg9McYz0fQcgv5SeVVCQ/viewform)
* 📊 **Application Tracking Dashboard:** [Open Dashboard](https://script.google.com/macros/s/AKfycbxQSRBzhl3-APfOnU-GB9LOUqyTPEBVmydvaGox5eQ/dev)
* 🌐 **Portfolio:** [Rohit Adhav Portfolio](https://sites.google.com/view/rohitadhav/home)
* 💻 **GitHub:** [RohitAdhav7935](https://github.com/RohitAdhav7935)
* 🔗 **LinkedIn:** [Rohit Adhav](https://www.linkedin.com/in/rohitradhav)

## ✨ Features

* 📩 Automated job application emails through Gmail
* 📄 CV selection based on the job role
* 📎 Automatic PDF attachment from Google Drive
* 📊 Application tracking using Google Sheets
* 🔄 Email status tracking: Sent, Failed, and Processing
* 📈 Application history dashboard
* 🏢 Company-wise and date-wise filters
* 🔍 Search by company name, HR email, or job role
* 📌 KPI cards displaying application statistics
* 🌙 Dark-themed dashboard interface

## 🛠️ Technology Stack

| Technology         | Purpose                                      |
| ------------------ | -------------------------------------------- |
| Google Forms       | Collect job application details              |
| Google Sheets      | Store application records and email statuses |
| Google Drive       | Store CV PDF files                           |
| Gmail              | Send job application emails                  |
| Google Apps Script | Automate emails and process application data |
| HTML               | Build the dashboard structure                |
| CSS                | Style the dashboard interface                |
| JavaScript         | Implement dashboard interactions             |
| GitHub             | Version control and project documentation    |

## 🔄 Project Workflow

1. Enter job application details through Google Forms.
2. Store submitted information in Google Sheets.
3. Process the submission using Google Apps Script.
4. Select the appropriate CV PDF from Google Drive based on the job role.
5. Send the application email through Gmail with the selected CV attached.
6. Record the email status and application details in Google Sheets.
7. Open the dashboard to monitor application history and statistics.
8. Filter and search application records by company, date, HR email, or job role.

## 📂 Project Structure

```text
Smart-HR-Email-Automation/
│
├── Dashboard.gs
├── EmailAutomation.gs
├── Index.html
├── Documentation/
├── Screenshots/
└── README.md
```

## ⚙️ Setup Instructions

1. Create a Google Form to collect job application details.
2. Link the form to a Google Sheets spreadsheet.
3. Upload your CV PDF files to Google Drive.
4. Create a Google Apps Script project.
5. Add the required CV PDF file IDs and map them to the appropriate job roles.
6. Configure the spreadsheet ID and sheet name in the script.
7. Set up an installable form-submission trigger.
8. Authorize the required Google services and permissions.
9. Deploy the dashboard as a Google Apps Script web app.
10. Configure appropriate access permissions and test the complete workflow.

## 🔐 Security and Privacy

* Do not publish private CV files or personal information.
* Keep HR contact details and application records private.
* Never commit credentials, authorization tokens, or sensitive configuration data to GitHub.
* Restrict access to the Google Sheets spreadsheet and Google Drive files.
* Configure appropriate access permissions before deploying the dashboard.
* Review the web app's deployment settings before sharing the dashboard publicly.

**Note:** The dashboard link currently uses the `/dev` endpoint, which is intended for development and testing by users with access to the Apps Script project. For broader access, deploy a production version and share its `/exec` URL with the appropriate permissions.

## 🎯 Project Objective

The objective of this project is to reduce repetitive manual work during job applications, improve email management, and provide a centralized dashboard for tracking application activity.

It demonstrates the practical use of workflow automation, cloud-based data management, web dashboard development, and Google Workspace integration.

## 👨‍💻 Author

**Rohit R. Adhav**

* 🌐 Portfolio: https://sites.google.com/view/rohitadhav/home
* 💻 GitHub: https://github.com/RohitAdhav7935
* 🔗 LinkedIn: https://www.linkedin.com/in/rohitradhav

---

⭐ If you find this project useful, consider starring the repository on GitHub.

```

### Before publishing

**One important point:** Your dashboard URL ends with `/dev`. That is a development URL, not the usual production deployment URL.

For a portfolio project, I recommend:
1. Open your Google Apps Script project.
2. Go to **Deploy → New deployment**.
3. Select **Web app** and configure the appropriate access permissions.
4. Deploy the application and copy the production URL ending in `/exec`.
5. Replace the dashboard link in your README with that URL.

Also, verify that the Google Form is accepting responses and that the dashboard opens for your intended audience before publishing the links on GitHub.
```
