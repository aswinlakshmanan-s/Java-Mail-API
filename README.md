# Java-Mail-API

This Java code is a part of a project related to mailing notifications. Specifically, it provides a class named Mailer with a method SendEmailOfNotification designed to send email notifications to users. The method takes a User object containing user details and a String specifying a facility for which the booking confirmation is being sent.

The code utilizes JavaMail API to interact with an email server, and it is configured to work with a Gmail account. It includes the sender's email address, username, password (in this case, an application-specific password), and SMTP server details. The email message is constructed with information about the booking confirmation, including the user's name, booked facility, and a thank-you message.

Additionally, a main method is included for an example usage of the Mailer class, demonstrating how to create a User object and send a notification email for a hypothetical booking of the "Swimming Pool" facility.
