# Jordan_Ahern_CSVAgg


Overview
This Jupyter Notebook automates fetching and processing unread emails with CSV attachments by appending their contents to specified CSV files. It filters emails based on a password included in the subject line and subject-specific keywords.

Prerequisites
Before running the notebook, ensure you have the following:

Python 3.x, Jupyter Notebook
Required libraries: pandas, imaplib, email.


Configuration and Usage

Email Configuration

Enable IMAP on your email account (e.g., Gmail via Settings > Forwarding and POP/IMAP).
App Password: If 2FA is enabled, generate an app password in your email account settings under Security.

Local Setup

Credentials: Input your email credentials in the notebook (username, password for the email account).
Password File: Create a password.txt in the notebook's directory with the password required in the email subjects.

Running the Notebook

Open your terminal, run jupyter notebook, and navigate to the notebook file to execute it.

User Adjustments

Email Keywords: Modify the csv_paths dictionary in the notebook to match your file paths and keywords.
Password: Ensure the password.txt matches the password in the subjects of emails you wish to process.
