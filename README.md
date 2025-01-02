# Signup Form Project  

A responsive and interactive multi-step signup form created using *HTML, CSS, and JavaScript*. The project validates user input, checks password strength, and ensures smooth navigation between different steps of the form.  

## Technologies Used
   - **HTML5** - For the strusture of the forms.
   - **CSS3** - For styling and responsive design.
   - **JavaScript** - For form validation and client-side functionality.

## Overview 

The project consists of multiple pages for:

1. **Signup (Step 1 & 2)** - A two step signup form with input validation.
2. **Signin** - A signin form with basic validation for username and password.
3. **Forgot Password** - A form to request an OTP for password reset.

Each form is styled with CSS for a minimal yet elegant look. JavaScript is used to implement form validation and navigation between signup steps.

## Features  
- *Form Validation*  
  - Username must be at least 3 characters.  
  - Email validation using regex.  
  - Password must be at least 6 characters.  
  - Password and Confirm Password must match.  
  
- *Multi-Step Form*  
  - Step 1: Username and Email.  
  - Step 2: Password and Confirm Password.  

- *Interactive Feedback*  
  - Alerts for invalid inputs.  
  - Prevents form submission on errors.  

- *Responsive Design*  
  - Adapts to different screen sizes.  
  - Mobile-friendly with responsive breakpoints.  

## Folder Structure 
*Signup-Form-Project*
    - Signup.html
    - Signup2.html
    - Signin.html
    - Forgot-password.html
    - Signup.css

## File Descriptions  
- *Signup.html* – Step 1 of the signup form (Username and Email).  
- *signup2.html* – Step 2 of the signup form (Password and Confirm Password).  
- *Signin.html* – Sign-in page for existing users.  
- *Forgot-password.html* – Forgot password page to request OTP.  
- *Signup.css* – Stylesheet to enhance the form design and responsiveness.  

## Validation and Logic  
- JavaScript is used to handle form validation.  
- Basic email regex is used for validating email addresses.  
- Passwords are checked for minimum length and matching fields.  
- Prevents form submission if validation fails.  

## Usage
1. **Download or clone** the repository.
2. Open Signup.html in a web browser to start the signup process.
3. Navigate between pages to test the signin and forgot password functionalities.
4. Customize the form styles by editing the Signup.css file.

## Notes

* Make sure to update the file paths in the HTML <link> and <a> tags if you move files to different directories.
* Basic validations for email format and password length are included. Additional server-side validation is recommended for production environments.

## Author  
*Dharmik*  
- Email: dharmikdolia183@gmail.com
- GitHub: https://github.com/DharmikDevops

Feel free to reach out for any suggestions or collaboration!
