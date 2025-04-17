# Shift Management - Test Cases

| Test Case ID | Module           | Test Case Description                              | Expected Result                                         | Status                     | Priority | Notes |
|--------------|------------------|-----------------------------------------------------|---------------------------------------------------------|----------------------------|----------|-------|
| DASH_TC_047  | Shift Management | User selects drawer from dropdown                  | Selected drawer should be active                        | Pass                       | Medium   |       |
| DASH_TC_048  | Shift Management | User adds a new drawer                             | Drawer should be added and visible in list              | Pass                       | Medium   |       |
| DASH_TC_049  | Shift Management | User performs cash in and cash out actions         | Cash transactions should be logged                      | Pass                       | High     |       |
| DASH_TC_050  | Shift Management | User enters cash in drawer                         | Amount should reflect in drawer balance                 | Pass                       | High     |       |
| DASH_TC_051  | Shift Management | User performs cash out action                      | Cash out should deduct from drawer                      | Fail in early build, then Pass | High |       |
| DASH_TC_052  | Shift Management | User views total amount in drawer                  | Drawer balance should be displayed accurately           | Fail in early build, then Pass | High |       |
| DASH_TC_053  | Shift Management | User submits cash                                  | Amount should be submitted and logged                   | Fail in early build, then Pass | High |       |
| DASH_TC_054  | Shift Management | User clicks 'Start Day' to start shift             | 'Start Day' should initialize shift session             | Pass                       | High     |       |
| DASH_TC_055  | Shift Management | User clicks 'Cancel' to exit shift management      | Shift window should close without saving                | Pass                       | Low      |       |
| DASH_TC_056  | Shift Management | User changes language to Arabic                    | UI should reflect Arabic translation                    | Fail in early builds, then Pass | Low  |       |
