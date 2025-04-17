
# Dashboard Module Test Cases

## Overview
This document contains test cases for the Dashboard module, covering functionality from login to specific dashboard features across multiple build versions.

---

## Test Case Summary

### 1. **User Login**
- **Description:** On successful login, the dashboard screen should open.
- **Status Across Builds:** Tested from build 3.6.4 to 3.08.65

### 2. **General Options**
- **Description:** Should be visible on the main dashboard page.
- **Status:** Mostly Pass across all builds.

### 3. **Total Sales**
- **Description:** Shows total sales for the day.
- **Status:** Pass on all tested builds.

### 4. **Total Expense**
- **Description:** Displays total expenses with detailed records.
- **Status:** Mixed results (Fail in 3.6.10, 3.6.11; Not tested in 3.6.35)

### 5. **Total Products**
- **Description:** Shows available products in the user's store.
- **Status:** Pass across builds.

### 6. **Sale Return**
- **Description:** Displays the returned products to the store.
- **Status:** Varies with some backend failures and untested statuses.

### 7. **Select Location**
- **Description:** Dropdown for selecting the store location.
- **Status:** Pass across all builds.

### 8. **Shift Option**
- **Description:** Allows the user to choose between today's or yesterday's shift.
- **Status:** Pass across all builds.

### 9. **New Order**
- **Description:** Used to place a new order.
- **Status:** Pass across all builds.

### 10. **Online Order**
- **Description:** Displays online orders.
- **Status:** Pass across all builds.

### 11. **Sales Return (Detailed)**
- **Description:** User can check product returns by entering the order number.
- **Status:** Mostly pass; backend issues noted in some builds.

### 12. **Order Adjustment**
- **Description:** Displays order adjustments by order number.
- **Status:** Backend issues noted in a few builds.

### 13. **Add Product**
- **Description:** Adds a new product to the system.
- **Status:** Minor backend error in one build; mostly pass.

### 14. **Add Purchase**
- **Description:** Records a new vendor purchase.
- **Status:** Pass with some backend errors noted.

### 15. **Record Expense**
- **Description:** Shows recorded expenses for the day.
- **Status:** Pass across all builds.

### 16. **Barcode Printing**
- **Description:** Initiates barcode printing for products.
- **Status:** Not tested in many builds; dependent on printer availability.

### 17. **Cash Drawer**
- **Description:** Select and interact with the cash drawer.
- **Status:** Pass across builds.

### 18. **Customer Display**
- **Description:** Displays customer-facing screen.
- **Status:** Pass across builds.

---

## Notes:
- "Not tested" or "Fail" indicates either feature unavailability or backend issues in specific builds.
- Ensure backend connectivity and device availability (like barcode printers) for complete feature validation.

