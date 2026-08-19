# 🧪 Test Cases: E-Commerce Web Application

---

### TC-001: Verify User Registration with Valid Data
- **Priority:** High
- **Type:** Functional / Positive
- **Preconditions:** User is on the Registration page.

| Step | Action | Expected Result |
| :--- | :--- | :--- |
| 1 | Enter valid First Name, Last Name, and Email | Inputs are accepted without errors |
| 2 | Enter a valid Password (e.g., `Password123!`) | Password strength indicator shows "Strong" |
| 3 | Click on the "Register" button | User account is created; redirected to Dashboard |

---

### TC-002: Verify Product Search Functionality
- **Priority:** High
- **Type:** Functional / Positive
- **Preconditions:** User is on the Home page.

| Step | Action | Expected Result |
| :--- | :--- | :--- |
| 1 | Type "Wireless Headphones" in Search bar | Autocomplete suggestions appear |
| 2 | Press "Enter" or click Search icon | Search result page displays relevant products |
| 3 | Apply "Price: Low to High" filter | Products are re-ordered correctly by price |

---

### TC-003: Verify Shopping Cart Item Quantity Update
- **Priority:** Medium
- **Type:** Functional / Positive
- **Preconditions:** User has added 1 item to the Shopping Cart.

| Step | Action | Expected Result |
| :--- | :--- | :--- |
| 1 | Navigate to Shopping Cart page | Item is displayed with quantity = 1 |
| 2 | Change quantity counter from 1 to 3 | Subtotal and Total price update automatically |
| 3 | Refresh the browser page | Quantity remains 3 |
