## Process
This automation project is designed to read the unread emails in the outward recipient's inbox and deliver a unique message based on the code word/words included in the email to another e-mail that you will read

## Steps
1: An e-mail from an outside source will be sent to the outward recipient email that either contains the selected code words, doesn't contain them or is blank

![image](https://github.com/0Domlightning0/Automation/assets/99225898/7451a61e-2c88-499d-91d1-5d98b03197ec)

2: The automation program will access the unread emails inside of the outward recipient's email and marks the accessed e-mail for reading to prevent repetition 

![image](https://github.com/0Domlightning0/Automation/assets/99225898/1abbecdc-cc71-47a4-bfd0-b555db291433) ![image](https://github.com/0Domlightning0/Automation/assets/99225898/b3a0e82c-c3be-4fd6-8e78-2d4ee73db6de) ![image](https://github.com/0Domlightning0/Automation/assets/99225898/b94ea6a8-63c0-4393-91a5-09f6f6d99647)



3: The automation program will look to see if any part of the email(Topic, Body) contains any of the code words, the program also will look to see if the email is blank

![image](https://github.com/0Domlightning0/Automation/assets/99225898/9b867af2-5e86-41d9-8c98-0ee1f19743d5) ![image](https://github.com/0Domlightning0/Automation/assets/99225898/57d2cca3-55ce-4f91-b61e-ced37c5f5613)

4: The automation program will set the message(msg. paylod) and topic(msg. topic to different text based on what code word was used to prepare to be sent

![image](https://github.com/0Domlightning0/Automation/assets/99225898/bfbf166a-8bd1-4b8f-8600-19e7b04458cb) ![image](https://github.com/0Domlightning0/Automation/assets/99225898/2d64445c-1aea-4aae-8971-ab5a9cd9d2e8)


5: The automation program will use the outward recipient email to send that new message to the inward recipient email 

![image](https://github.com/0Domlightning0/Automation/assets/99225898/551334fc-2b67-4b7a-be8b-3676f6891f9c) ![image](https://github.com/0Domlightning0/Automation/assets/99225898/1496b923-a87f-4aa8-bed8-a4b91f4722d1)

## Vocabulary
UserID = email address of the email you are trying to log into 

Folder = What folder of the email you are trying to access ex. SPAM, STARRED, ALL MAIL

outward recipient email = The email address receiving emails that are not from you

inward recipient email = The email that your program is sending the results to, the one you read

msg. payload = The Body/main part of the email/message

msg. topic = The subject/topic of the email/message

# Making changes 

## Changing the outward recipient email

Change the current UserId and password to your own email and passwrd to that email. You may need to get an alternate password in order to access your email on Node-Red

![image](https://github.com/0Domlightning0/Automation/assets/99225898/9406351f-c464-4602-bcf5-7d319fcf5ff5)

### Getting an alternate password

1: Enter your google account and go to the security 

2: Go down to two-factor authorization and activate it using your phone number

3: Go down to App passwords and click on it

4: Create a password for your email and write down a custom name

5: Copy and paste that password into the password section in Node-red 

## Changing the code words 

You can change the string where "Paris" is to any word or string

![image](https://github.com/0Domlightning0/Automation/assets/99225898/00f462d8-cff2-43da-83b6-cd4d45e514e6)

## Changing how it detects code words 

You can change the requirements around the code words using the dropdown menu to the left of "Paris"

![image](https://github.com/0Domlightning0/Automation/assets/99225898/74bd4fab-787f-4481-ab0a-7c644afc3b14)

## Changing what folder the email reads

You can change the folder the program reads by changing the input in the FOLDER menu

![image](https://github.com/0Domlightning0/Automation/assets/99225898/041a18da-45f0-4384-9ccf-42dd279f94a5) ![image](https://github.com/0Domlightning0/Automation/assets/99225898/a12b7329-16a8-41c2-adfc-2dd61815b4ff)

## Changing the body and topic of the email sent to the inward recipient email

### Changing body

You can change the message's body by changing the string value under msg. payload, this will be the message inside the body of the email

![image](https://github.com/0Domlightning0/Automation/assets/99225898/ad43cbdd-b337-4b6d-a708-5062a573b41f)

### Changing topic

You can change the message's body by changing the string value under msg. topic, this will be the message inside of the subject of the email

![image](https://github.com/0Domlightning0/Automation/assets/99225898/36a1fd46-1e60-4bad-aedb-b798c091a9dd)

## Changing the inward recipient email

You can change the inward recipient by changing the email address in the "To" menu

![image](https://github.com/0Domlightning0/Automation/assets/99225898/bd70add0-5ea8-4d4b-950d-eb6194030e0c)

















