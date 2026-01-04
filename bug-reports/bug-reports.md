---

## BUG-01: Login error message text overflows container

**Severity:** Low  
**Priority:** Low  
**Status:** Open  
**Type:** UI / Usability  

### Steps to Reproduce
1. Navigate to the login page  
2. Enter a valid username  
3. Enter an invalid password  
4. Click the Login button  

### Expected Result
A clear validation message is displayed indicating that the password is incorrect, with all text fitting within the message container.

### Actual Result
The validation message is displayed, but the text overflows the message container and does not fit within the allocated space.

**Screenshot**
<img width="233" height="164" alt="WrongPasswordBug" src="https://github.com/user-attachments/assets/90c236eb-b641-46c3-a9e0-bc146597229d" />

### Environment
- Browser: Google Chrome (latest)
- Operating System: Windows 11
- Device: Laptop

### Attachments
- Screenshot showing text overflow issue
