| Test Case ID         | Module          | Test Case Description                                                          | Expected Result                                              | Status | Priority | Notes             |
|----------------------|-----------------|----------------------------------------------------------------------------------|--------------------------------------------------------------|--------|----------|--------------------|
| TC-OPT-001           | Options         | User should be able to access general options                                  | Options screen is accessible                                 | Pass   | High     |                    |
| TC-OPT-002           | Options         | Add Product functionality                                                      | Product is added successfully                                | Pass   | High     |                    |
| TC-OPT-003           | Options         | Sales Return functionality                                                     | Sales return interface opens                                 | Pass   | High     |                    |
| TC-OPT-004           | Options         | Order Adjustment functionality                                                 | Order adjustment interface opens                             | Pass   | Medium   |                    |
| TC-OPT-005           | Options         | Record Expense functionality                                                   | Expense interface opens                                      | Pass   | Medium   |                    |
| TC-OPT-006           | Options         | Add Purchase functionality                                                     | Purchase screen opens                                        | Pass   | High     |                    |
| TC-OPT-007           | Options         | Order History functionality                                                    | Order history screen loads                                   | Pass   | High     |                    |
| TC-OPT-008           | Options         | GRN (Goods Received Notes)                                                     | GRN section loads successfully                               | Pass   | High     |                    |

---

**Order History (Complete Orders)**

| Test Case ID         | Module             | Test Case Description                                                | Expected Result                                         | Status | Priority | Notes |
|----------------------|--------------------|------------------------------------------------------------------------|---------------------------------------------------------|--------|----------|-------|
| TC-OH-001            | Order History      | Shows Order Number                                                   | Order number is displayed                               | Pass   | High     |       |
| TC-OH-002            | Order History      | Shows Payment Method                                                 | Payment method shown                                    | Pass   | High     |       |
| TC-OH-003            | Order History      | Shows Tax                                                            | Applied tax is shown                                    | Pass   | Medium   |       |
| TC-OH-004            | Order History      | Shows Amount                                                         | Total order amount is shown                             | Pass   | High     |       |
| TC-OH-005            | Order History      | Action options                                                       | Available options (e.g., Print, Return) are shown       | Pass   | High     |       |
| TC-OH-006            | Order History      | Print functionality                                                  | Print dialog opens                                      | Pass   | High     |       |
| TC-OH-007            | Order History      | Sales Return from complete order                                     | Sales return flow initiates                             | Pass   | High     |       |
| TC-OH-008            | Order History      | Order Adjustment from complete order                                 | Adjustment interface opens                              | Pass   | Medium   |       |

---

**Rejected Orders**

| Test Case ID         | Rejected Orders    | Test Case Description                                                | Expected Result                                 | Status | Priority | Notes |
|----------------------|--------------------|------------------------------------------------------------------------|-------------------------------------------------|--------|----------|-------|
| TC-RO-001            | Rejected Orders    | Shows Order Number of rejected orders                                | Rejected order number shown                     | Pass   | Medium   |       |
| TC-RO-002 to 005     | Rejected Orders    | Empty fields: Payment Methods, Tax, Amount, Action                   | Fields remain empty                             | Pass   | Low      |       |

---

**Return Orders**

| Test Case ID         | Return Orders      | Test Case Description                                                | Expected Result                                         | Status | Priority | Notes |
|----------------------|--------------------|------------------------------------------------------------------------|---------------------------------------------------------|--------|----------|-------|
| TC-RTO-001           | Return Orders      | Shows Order Number of returned orders                               | Order number visible                                    | Pass   | High     |       |
| TC-RTO-002           | Return Orders      | Shows Payment Method                                                 | Payment method shown                                    | Pass   | High     |       |
| TC-RTO-003           | Return Orders      | Shows Tax                                                            | Tax displayed                                           | Pass   | Medium   |       |
| TC-RTO-004           | Return Orders      | Shows Amount                                                         | Amount of order shown                                   | Pass   | High     |       |
| TC-RTO-005           | Return Orders      | Shows Action options                                                 | Available actions shown                                 | Pass   | High     |       |

---

**Quotation Orders**

| Test Case ID         | Quotations         | Test Case Description                                                | Expected Result                                         | Status | Priority | Notes |
|----------------------|--------------------|------------------------------------------------------------------------|---------------------------------------------------------|--------|----------|-------|
| TC-QO-001            | Quotation          | Shows Order Number                                                   | Quotation order number displayed                        | Pass   | High     |       |
| TC-QO-002            | Quotation          | Shows Payment Method                                                 | Payment method visible                                  | Pass   | Medium   |       |
| TC-QO-003            | Quotation          | Shows Tax                                                            | Tax shown on quotation                                  | Pass   | Medium   |       |
| TC-QO-004            | Quotation          | Shows Total                                                          | Total amount displayed                                  | Pass   | High     |       |
| TC-QO-005            | Quotation          | Shows Actions                                                        | Actions available (e.g., Print, Adjust)                 | Pass   | High     |       |
| TC-QO-006            | Quotation          | Print functionality                                                  | Print dialog opens                                      | Pass   | Medium   |       |
| TC-QO-007            | Quotation          | Order Adjustment                                                     | Order adjustment opens                                  | Pass   | Medium   |       |

---

**GRN - Good Received Notes**

| Test Case ID         | GRN                | Test Case Description                                                | Expected Result                                         | Status       | Priority | Notes                 |
|----------------------|--------------------|------------------------------------------------------------------------|---------------------------------------------------------|--------------|----------|------------------------|
| TC-GRN-001           | GRN                | Shows Order Number of purchase order                                | Purchase order number displayed                         | Pass         | High     |                        |
| TC-GRN-002           | GRN                | Clicking order number shows order details in popup                   | Order detail popup shown                                | Pass         | Medium   |                        |
| TC-GRN-003           | GRN                | Shows Received At date                                               | Received at date displayed                              | *To be implemented* | Medium   | Expected in future build |
| TC-GRN-004           | GRN                | Shows Created At date                                                | Created at date displayed                               | *To be implemented* | Medium   | Expected in future build |
| TC-GRN-005           | GRN                | Shows action buttons                                                 | Available actions visible                               | Pass         | High     |                        |
| TC-GRN-006           | GRN                | Barcode printing only if marked received                             | Works only after marking as received                    | Pass         | High     |                        |
| TC-GRN-007           | GRN                | Mark as Received enables barcode print                               | Works as expected                                       | Pass         | High     |                        |
| TC-GRN-008           | GRN                | PDF Download of order                                                | PDF file is downloaded                                  | Pass         | Medium   |                        |
