# Access Control Vulnerabilities

Access control enforces policy such that users cannot act outside of their intended permissions.  
Failures typically lead to:

- Unauthorized information disclosure  
- Modification or destruction of data  
- Performing a business function outside the user's limits  

## Common Access Control Vulnerabilities

### 1. Violation of the Principle of Least Privilege
- Also known as **deny by default**
- Access should only be granted for specific:
  - Capabilities  
  - Roles  
  - Users  
- In practice, access is sometimes available to **anyone**

---

### 2. Bypassing Access Control Checks
This can occur by modifying:

- The URL *(parameter tampering or force browsing)*
- Internal application state  
- The HTML page  
- API requests using attack tools  

---

### 3. Insecure Direct Object References (IDOR)
- Permitting viewing or editing someone else's account  
- Achieved by providing its **unique identifier**

---

### 4. Missing Access Controls on APIs
- APIs accessible without proper restrictions for:
  - `POST`  
  - `PUT`  
  - `DELETE`  

---

### 5. Elevation of Privilege
- Acting as a user **without being logged in**  
- Gaining privileges beyond those expected, for example:
  - Standard user obtaining **admin access**

---

### 6. Metadata Manipulation
Examples include:

- Replaying or tampering with a **JSON Web Token (JWT)**
- Manipulating:
  - Cookies  
  - Hidden fields  
- Abusing **JWT invalidation**

---

### 7. CORS Misconfiguration
- Allows API access from:
  - Unauthorized origins  
  - Untrusted origins  

---

### 8. Force Browsing
- Guessing URLs to access:
  - Authenticated pages as an unauthenticated user  
  - Privileged pages as a standard user  