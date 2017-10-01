### [GMAIL Test Scenarios](http://artoftesting.com/manualTesting/gmail.html)

## Test Scenarios for Inbox Functionality(Receive Email)

    Verify that a newly received email is displayed as highlighted in the Inbox section.
    Verify that a newly received email has correctly displayed sender emailId or name, mail subject and mail body(trimmed to single line).
    Verify that on clicking the newly received email, user is navigated to email content.
    Verify that the email contents are correctly displayed with the desired source formatting.
    Verify that any attachments are attached to the email and is downloadable.
    Verify that the attachments are scanned for viruses before download.
    Verify that all the emails marked as read are not highlighted.
    Verify that all the emails read as well as unread have a mail read time appended at the end on the email list displayed in the inbox section.
    Verify that count of unread emails is displayed alongside 'Inbox' text in left sidebar of GMail.
    Verify that unread email count increases by one on receiving a new email.
    Verify that unread email count decreases by one on reading an email ( marking email as read).
    Verify that email recipients in cc are visible to all user.
    Verify that email recipients in bcc are not visible to user.
    Verify that all received emails get piled up in the 'Inbox' section and gets deleted in cyclic fashion based on the size availability.
    Verify that email can be received from non-gmail emailIds like - yahoo, hotmail etc.

## Test scenarios for Compose mail Functionality

    Verify that on clicking 'Compose' button, a frame to compose a mail gets displayed.
    Verify that user can enter emailIds in 'To', 'cc' and 'bcc' sections and also user will get suggestions while typing the emailds based on the existing emailIds in user's email list.
    Verify that user can enter multiple comma separated emailIds in 'To', 'cc' and 'bcc' sections.
    Verify that user can type Subject line in the 'Subject' textbox.
    Verify that user can type the email in email-body section.
    Verify that user can format mail using editor-options provided like choosing font-family, font-size, bold-italic-underline etc.
    Verify that user can user can attach file as an attachement to the email.
    Verify that user can add images in the email and select the size for the same.
    Verify that after entering emailIds in either of the 'To', 'cc' and 'bcc' sections, entering Subject line and mail body and clicking 'Send' button, mail gets delivered to intended receivers.
    Verify that sent mails can be found in 'Sent Mail' sections of the sender.
    Verify that mail can be sent to non-gmail emailIds also.
    Verify that all sent emails get piled up in the 'Sent Mail' section and gets deleted in cyclic fashion based on the size availability.
    Verify that the emails composed but not sent remain in the draft section.
    Verify the maximum number of email recepients that can be entered in 'To', 'cc' and 'bcc' sections.
    Verify the maximum length of text that can be entered in the 'Subject' textbox.
    Verify the content limit of text/images that can be entered and successfully delivered as mail body.
    Verify the maximum size and number of attachement that can be attached with an email.
    Verify that only the allowed specifications of the attchement can be attached with an email/
    Verify that if email is sent without Subject, a pop-up is generated warning user about no subject line. Also, verify that on accepting the pop-up message, user is able to send the email.
