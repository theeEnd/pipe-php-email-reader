# pipe-php-email-reader

-------------------------------------

Recieve mail and attachments with PHP

Usage
-------------------------------------
email_script.php contains the class EmailPipe that works with the incoming email. 

Make this script executable.

Configure your mail server to pipe emails to this script. See
http://stuporglue.org/add-an-email-address-that-forwards-to-a-script/
for instructions.  

api.php contains the class Api that read, searches already saved emails in DataBase.

Accepts POST and GET parameters. 
Expects two parameters action and value.
Example api.php?action=get_email&value=mail.bg
Types of actions are declared as constants in include / Api.php

-------------------------------------

