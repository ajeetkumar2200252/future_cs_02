# future_cs_02
"Excited to share my latest insights on setting up phishing campaigns with GoPhish! Learn how to create sending profiles, landing pages, and email templates to enhance your cybersecurity training. Let's strengthen our defenses together!"

Configuring the Email Sending Profile
Name: Choose a recognizable name for the profile.
From: Use a credible email address that appears legitimate.
Host: Enter the SMTP server address (e.g., smtp.example.com).
Username/Password: Input the credentials for the email account.
Click "Save Profile" 

Creating a Phishing Landing Page
The landing page is where users are redirected after clicking the phishing email link. It’s designed to look like a legitimate login page while capturing credentials.In GoPhish, go to “Landing Pages” and click “New Page.” Give it a name like ACME Login. Then, click "Source" to edit the HTML.

Creating an Email Template
Access the "Email Templates" section and click on "+ New Template."
Fill in the subject line and body of the email, 
Click "Save Template" to store your email design.

create a User Group
Navigate to "Users & Groups" and click on "+ New Group."
You can import users via a CSV file or add them manually.
Ensure the format is correct, including headers like First Name, Last Name, and Email.
Save the group once all users are added.

Launching the Campaign
Go to the "Campaigns" section and click on "+ New Campaign."
Select the previously created email template, landing page, and user group.
Set the launch date and time or choose to send immediately.
Click "Launch Campaign" to start the phishing test.
