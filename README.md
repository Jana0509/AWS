# 4 Crucial Steps to Secure, Manage, and Budget Your Cloud Journey in AWS 


# Introduction:
Imagine setting sail on a powerful ship named AWS Cloud! You’ve just got the keys to the captain’s cabin (Root Account), but before you dive into exploring the vast ocean of AWS services, there are some essential tasks to ensure your ship is safe, secure, and ready for the adventure ahead. Let’s buckle up and explore **4 critical things you must do right after creating your AWS account** — your ultimate treasure map to smooth sailing in the cloud world.

![image](https://github.com/user-attachments/assets/f8ffe327-1524-4265-821e-5ee4b317da66)

# 4 Key Steps After Creating an AWS Account
**1. Secure Your Root Account**
Your Root Account is like the master key to the entire ship — it has unlimited powers. So, securing it is the top priority. Adding **Multi-Factor Authentication (MFA)** adds a protective shield to keep your treasures (data) safe.

Root User can perform any sensitive operations in your account, adding an extra layer of authentication will helps to secure your account. So, enabling MFA for Root user and IAM user will be recommended and must.

**Steps to Enable MFA:**

Go to your Security Credentials page from the AWS console.

![image](https://github.com/user-attachments/assets/c8e84724-8f69-4ddd-80df-74813eb9bb34)


**2. Choose Assign MFA**

![image](https://github.com/user-attachments/assets/93380a3d-ec64-4c6e-a961-b67cf6c77dd9)


3. Enter the two MFA codes displayed by your app and click **Add MFA**.

4. Install a compatible application such as **Google Authenticator**, Duo Mobile, or Authy on your mobile device or computer. Verify your device’s compatibility here, then enter two consecutive MFA codes in the provided text boxes.

   ![image](https://github.com/user-attachments/assets/bf78bab9-e131-4455-a437-447b97e68fff)
