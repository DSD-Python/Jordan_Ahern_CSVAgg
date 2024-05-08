# Jordan_Ahern_CSVAgg


Overview
This Jupyter Notebook automates fetching and processing unread emails with CSV attachments by appending their contents to specified CSV files. It filters emails based on a password included in the subject line and subject-specific keywords.

Prerequisites
Before running the notebook, ensure you have the following:

Python 3.x, Jupyter Notebook
Required libraries: pandas, imaplib, email.


Configuration and Usage

Email Configuration

Enable IMAP on your email account (e.g., Outlook via Settings > Forwarding and POP/IMAP).
The current host information is configured for Outlook. However, other imap_host addresses are easily accessable. 
App Password: If 2FA is enabled (which it should be!), generate an app password in your email account settings under Security.

Local Setup

Credentials: Input your email credentials in the notebook (username, password for the email account).
Key File: Create a key.txt in the notebook's directory with the password required in the email subjects.

Running the Notebook

Open your terminal, run jupyter notebook, and navigate to the notebook file to execute it.

User Adjustments

Email Keywords: Modify the csv_paths dictionary in the notebook to match your file paths and keywords.
Password: Ensure the password.txt matches the password in the subjects of emails you wish to process.

Issues?
For any further questions or feedback, please open an issue in the GitHub repository or contact ahernji@bc.edu


Other IMAP Server Addresses:
Gmail
IMAP Server: imap.gmail.com
Port: 993
SSL Required: Yes

Yahoo Mail
IMAP Server: imap.mail.yahoo.com
Port: 993
SSL Required: Yes

AOL Mail
IMAP Server: imap.aol.com
Port: 993
SSL Required: Yes

Zoho Mail
IMAP Server: imap.zoho.com
Port: 993
SSL Required: Yes

iCloud Mail
IMAP Server: imap.mail.me.com
Port: 993
SSL Required: Yes

ProtonMail (via ProtonMail Bridge)
IMAP Server: As provided by ProtonMail Bridge
Port: Typically 993
SSL Required: Yes

Fastmail
IMAP Server: imap.fastmail.com
Port: 993
SSL Required: Yes
