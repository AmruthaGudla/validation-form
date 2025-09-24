**Objective:** Validate form fields before submission.  
- **Task:** Validate email format and password length.  
- **Pseudo Code:**  
Step 1: Create error state variables → emailError, passwordError
Step 2: On form submit:
- If email does not match regex → set emailError
- If password length < 6 → set passwordError
Step 3: Display error messages below inputs
Step 4: If no errors → show "Form Submitted Successfully"
<img width="579" height="582" alt="Screenshot 2025-09-24 135044" src="https://github.com/user-attachments/assets/dd50e88e-3ddc-4c41-8fb5-a6d6b1222665" />
