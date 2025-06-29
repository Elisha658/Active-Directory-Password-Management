# Active Directory Password Reset Process  
*Demonstrating account unlock and forced password reset procedures*

---

## Step 1: Account Locked Out  
![Locked Account Notification](pass3.PNG)  
- User "Richard Hendricks" locked out after multiple failed login attempts  
- Common causes: Forgotten password or intrusion attempts  

---

## Step 2: Administrator Password Reset  
### Locate User in ADUC  
![AD User Search](pass2.png)  
- Open **Active Directory Users and Computers**  
- Find user → Right-click → **Reset Password**  

### Configure Password Settings  
![Password Reset Dialog](pass5.png)  
- Enter temporary password  
- Check: **User must change password at next logon**  
- Check: **Unlock account** (if locked)  

---

## Step 3: User Login Experience  
### Initial Login Prompt  
![Domain Selection](pass6.PNG)  
- User enters the temporary password which was given 

### Password Change Requirement  
![Forced Password Change](pass7.PNG)  
- User enters the new password before system grants access  

### Password Update Screen  
![Password Change Interface](pass8.PNG)  
- new secure password has been entered and user has been granted access
