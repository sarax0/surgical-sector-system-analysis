# Surgical Sector System Analysis

---
## Description

The Operating Sector System Analysis project optimizes the process of scheduling surgeries and managing patient information within the hospital environment. It streamlines the workflow from receiving sector lists to post-operative care, ensuring efficient utilization of resources and timely patient care.

The system begins by receiving lists of patients assigned for surgery from clinic sectors, including crucial details such as patient file numbers and physician names. These lists are then sent to the Medic for scheduling surgeries. The Medic accesses patient files to schedule appointments based on available beds, ensuring an orderly and efficient process.

Room availability is managed meticulously, with a dedicated effort to allocate rooms based on the type of operation and any necessary ICU bed reservations. If ICU preservation is required, the system verifies the availability of beds in the ICU sector, ensuring patient safety and appropriate post-operative care.

Additionally, the system facilitates the management of surgery items through coordination with the Stockbroker, ensuring adequate supplies and timely notifications in case of shortages.

Prior to surgery, patients undergo vital sign assessments by the anesthetist to determine their readiness. If deemed fit for surgery, appointments proceed as scheduled; otherwise, they are appropriately delayed to prioritize patient well-being.

On the day of surgery, the secretary confirms patient attendance and initiates the operation list. Patients are then escorted to the operating room by the nurse, where the Chief Surgeon retrieves their file and conducts the operation. Post-operation, the patient's status is updated, and recovery room arrangements are made as per protocol.

![Uploading image.png…]()

---
## Items and Attributes

The system manages various items and attributes crucial to the surgical process, including surgery items, room availability, and patient vital signs.

---

## Expected Output

Expected outputs include comprehensive lists of surgery items for specific operations and updated patient statuses post-operation, ensuring clarity and accountability throughout the process.

---
## Analysis Techniques

Utilizing techniques such as focus groups, the project delves into the intricacies of system flow and interrelated sectors like the Blood Bank, ICU, and NICU, providing valuable insights for optimization.

---
## User Role

User roles are defined to streamline operations, with roles such as the Anesthetist having the authority to approve surgeries after conducting necessary check-ups.

---
## ERD Diagram

The project includes an ERD diagram, depicting the relational database model and facilitating a better understanding of data organization and flow within the system.

![image](https://github.com/sarax0/surgical-sector-system-analysis/assets/122404545/31d90def-8573-47bd-bd86-7c0dc17ee82e)

---
## Stored Procedures

1. **Insert Into Login:** Inserts new login credentials into the system.
2. **Update Login:** Updates existing login credentials in the system.
3. **Insert Patient:** Adds a new patient record into the database.
4. **Insert Sector Patient:** Links a patient to a specific sector for scheduling purposes.
5. **Select Patient By Name:** Retrieves patient information based on their name.
6. **Delete Patient:** Removes a patient record from the system.
7. **Insert Employee:** Adds a new employee record to the hospital staff database.
8. **Select Employee By Name:** Retrieves employee information based on their name.
9. **Select All Employees:** Retrieves information about all employees in the system.
10. **Update Employee:** Updates existing employee information in the system.
11. **Delete Employee:** Removes an employee record from the system.
12. **Insert Surgery Item:** Adds a new surgery item to the inventory.
13. **Insert Tools:** Adds new surgical tools to the inventory.
14. **Update Surgery Items:** Updates information about existing surgery items.
15. **Update Surgery Items Part1:** Part 1 of the update process for surgery items.
16. **Update Surgery Items Part2:** Part 2 of the update process for surgery items.
---


