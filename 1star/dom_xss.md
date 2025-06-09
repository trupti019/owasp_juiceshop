#Title: DOM XSS
#Category: Cross-Site Scripting (XSS)

The "DOM XSS" challenge requires to perform a DOM-based XSS attack by injecting malicious JavaScript code into a web application's Document Object Model via an unfiltered input field, specifically targeting an iframe source attribute.

What i did here is injected the payload into the search bar and thats it!
It triggered an XSS alert

The payload was url encoded\.
![dom_xss_1](https://github.com/user-attachments/assets/67e68e50-9c24-43b4-ac97-411d4f4ddba4)
