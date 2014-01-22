gitubDocumentation
==================

This is a test documentation to learn how to use Github. 

The superuser is responsible only for creating and editing admin users and their roles. While installing the server, a superuser account is created by the installer with a password specified by the user. When the superuser logs into the console it is only given the option of editing admin users.

The superuser can no longer log into the browser. A normal user must be used for that purpose.
There's a backdoor to change the superuser's password:

Place a file named 'superuserPasswordReset' in execution directory of the server. This should contain the superuser's new password.

Within a few seconds the change is made, logged in using the new password, and the 'superuserPasswordReset' file will be securely deleted.

