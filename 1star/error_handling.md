#Title: Error Handling
#Category: Security Misconfiguration

Solved by two methods:

1.Using Wirehark:
 
Here, i provoked an error that reveals backend details due to improper error handling or nonsystematic erroe handling.

I followed these steps:

   1.Experiment with URL Paths: Accessed various non-existent or restricted URL paths on the application's server to trigger error responses.
   2.Carefully examined the error messages for any signs of verbose or detailed information leakage.
   3. entered a random name after i forwarded the request to the repeater which triggered the error

   ![image](https://github.com/user-attachments/assets/85c9f867-0da9-4bcf-8432-4f571fe2b7bb)

2. Tweaking website url:
   I just typed complete random nonsense in the url.
![image](https://github.com/user-attachments/assets/2085cc9e-bcc0-4452-a502-4ba40602f44e)
