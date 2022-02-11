## High Level Test Plan
| Test ID | Description | Input | Expected output | Actual Output |
| --- | --- | --- | --- | --- |
| 1 | Check patient registration status | 121 (aadhar no) | {-1} |  (not found) |
| 2 | Check patient registration status | 92 (aadhar no) | {0,1} |  (found) |
| 3 | Check patient vaccination status | 3 (patient id) | {>0} | (vaccinated) |
## Low Level Test Plan
| Test ID | Description | Input | Expected output | Actual Output |
| --- | --- | --- | --- | --- |
| 1 | Check patient registration status | 125 (aadhar no) | 0 | 0 (registered, not vaccinated) |
| 2 | Check patient registration status | 130 (aadhar no) | 1 | 1 (registered, vaccinated) |
| 3 | Check patient vaccination status | 3 (patient id) | 1 | 1 (first dose) |
| 4 | Check patient vaccination status | 3 (patient id) | 2 | 2 (second dose) |
| 5 | Check patient vaccination status | 3 (patient id) | 3 | 3 (already vaccinated) |

