#Title: Outdated Allowlist
#Category: Unvalidated Redirects

The task is to manipulate the URL to redirect to an unapproved or unintended cryptocurrency address by leveraging the weaknesses in the allowlist.

Tools used : Web browser and developer tools.

 The JavaScript code managing these QR codes, found within the main.js file, reveals that specific cryptocurrency addresses are hard-coded, and there is a redirect function that points to these addresses based on the user's selection.
![outdated_allowlist_1](https://github.com/user-attachments/assets/9aa5c459-51ff-4214-9dff-6db1cae27e86)

URL Manipulation:
Modified the redirect URL parameter to point to a new address that was on the allowlist.
