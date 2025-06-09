#Title: Missing Encoding
#Category: Improper Input Validation

This challenge ask us to retrieve a specific image from a web application that fails to load due to encoding issues in its URL.

This involves understanding how web browsers handle URLs and the importance of proper URL encoding.

I used an online url encoding tool here.
 Inspecting the element using browser developer tools showed that the src attribute of the image tag contained special characters (emoji) which were not URL encoded.


 I replaced the special charater (#) with %23

 Reloaded and verified the image
 ![missing_encoding_2](https://github.com/user-attachments/assets/da9e1e55-2230-4914-99b7-4f473b542f42)
