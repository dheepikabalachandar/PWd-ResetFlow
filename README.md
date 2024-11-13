# 🛡️ Secure Password Reset Flow: A User-Friendly Approach 🚀

Welcome to my project! I have developed a secure and user-friendly password reset process that prioritizes user experience without compromising on security. 

## 📝 Overview

1. **🔒 Forget Password Page**
   - We've designed a dedicated page for password recovery. Users enter their registered email ID.

2. **🔎 User Existence Verification**
   - The system validates the existence of the user in the database.
   - If the user is not found, an error message is displayed.

3. **📧 OTP Generation and Dispatch**
   - A unique One-Time Password (OTP) is generated and dispatched with a password reset link to the user's email.
   - The OTP is securely stored in the database for subsequent verification.

4. **👤 User Verification**
   - Upon clicking the link, the system extracts the OTP and validates it against the stored value.
   - If the OTP is valid, the password reset form is displayed. If not, an error message is shown.
  
 netlify link:   - password-reset-flows.netlify.app/


