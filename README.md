**Overview**

This project involved performing manual testing for an e-commerce website to identify and resolve functional and usability issues. The tests covered key features such as user authentication, security code validation, and accessibility compliance.

## Key Test Scenarios
	1.	Registration and Login:
	•	Verified the functionality of “Sign-Up” and “Login” options.
	•	Tested login with valid and invalid phone numbers, OTP codes, and empty fields.
	2.	Security Code Validation:
	•	Checked for unique, non-reusable, and hidden security codes during confirmation.
	•	Tested code expiry, incorrect code entries, and resending scenarios.
	3.	Accessibility Testing:
	•	Assessed login links for clear and meaningful text compatibility with screen readers.

## Tools and Techniques
	•	Browser: Chrome Version 131.0.6778.86 (64-bit).
	•	Testing Types: Functional, usability, and security testing.
	•	Accessibility Checks: Performed using manual inspection and screen readers.

## Results
	•	Critical Issues Identified:
	•	Missing “Sign-Up” option, restricting new user registrations.
	•	Login links lacked discernible text, impacting accessibility for screen readers.
	•	Only phone number login was available, limiting user flexibility.
	•	Usability Enhancements:
	•	Improved login icon visibility and user feedback for invalid inputs.
	•	Enhanced error messages for better clarity and guidance.

Recommendations
	1.	Add alternative login methods, such as email or social accounts.
	2.	Ensure all interactive elements are accessible with meaningful text for screen readers.
	3.	Secure OTP implementation to prevent code visibility during confirmation.
