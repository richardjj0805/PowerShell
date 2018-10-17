# PowerShell - Send Email

#Recipient List must be quoted, and comma delimited:
$recipient_list = "shijian.he@iqvia.com"
$from = "noreplymiportal@iqvia.com"
$smtpServer = "prodemail.rxcorp.com" #Note - this smtp server only allows us to send requests from white-listed hosts.
$subject = "Seiqurs - No Files"
$body = "This email is to advise that Seqirus Access DB is not ready "
SendEmail $from $recipient_list $subject $body $smtpServer
SendEmail $from $recipient_list $subject $body $smtpServer
