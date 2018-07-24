# opsview-slack-webhook
How to configure Opsview to send slack notifications via webhooks, with colored attachments
# Installing the file
sftp the file to the opsview server into the following location
/usr/local/nagios/libexec/notifications
# Configure Opsview to use he new script
1. log into opsview
2. navigate to notification methods
3. edit the slack notification methods
4. type in the new script name in the command field
5. reload opsview web via the roload button in the menu
