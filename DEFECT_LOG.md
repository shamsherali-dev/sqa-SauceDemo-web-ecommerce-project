Defect ID: BUG-WEB-001
Title: [Checkout] User can bypass cart validation and access Checkout Step 2 directly via URL
Severity: High | Priority: High
Module: Checkout & Navigation
Environment: Google Chrome v120 / Windows 11

Steps to Reproduce:
1. Navigate to https://www.saucedemo.com/ and log in as standard_user.
2. Ensure cart item count is 0.
3. Manually paste URL in address bar: https://www.saucedemo.com/checkout-step-two.html and press Enter.

Expected Result:
System should check for cart items, block direct access, and redirect user to inventory page with an error.

Actual Result:
System loads Checkout Overview page showing Item Total: $0.00 and allows clicking "Finish".

Screenshot/Evidence:
<img width="1574" height="665" alt="image" src="https://github.com/user-attachments/assets/90447050-100a-441e-b6ee-3f2a8f5b9c8e" />
