# Surgical Sector System Analysis

---

## Description

The Operating Sector System Analysis project optimizes the process of scheduling surgeries and managing patient information within the hospital environment. It streamlines the workflow from receiving sector lists to post-operative care, ensuring efficient utilization of resources and timely patient care.

The system begins by receiving lists of patients assigned for surgery from clinic sectors, including crucial details such as patient file numbers and physician names. These lists are then sent to the Medic for scheduling surgeries. The Medic accesses patient files to schedule appointments based on available beds, ensuring an orderly and efficient process.

Room availability is managed meticulously, with a dedicated effort to allocate rooms based on the type of operation and any necessary ICU bed reservations. If ICU preservation is required, the system verifies the availability of beds in the ICU sector, ensuring patient safety and appropriate post-operative care.

Additionally, the system facilitates the management of surgery items through coordination with the Stockbroker, ensuring adequate supplies and timely notifications in case of shortages.

Prior to surgery, patients undergo vital sign assessments by the anesthetist to determine their readiness. If deemed fit for surgery, appointments proceed as scheduled; otherwise, they are appropriately delayed to prioritize patient well-being.

On the day of surgery, the secretary confirms patient attendance and initiates the operation list. Patients are then escorted to the operating room by the nurse, where the Chief Surgeon retrieves their file and conducts the operation. Post-operation, the patient's status is updated, and recovery room arrangements are made as per protocol.

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

1. Insert Into Login
2. Update Login
3. Insert Patient
4. Insert Sector Patient
5. Select Patient By Name
6. Delete Patient
7. Insert Employee
8. Select Employee By Name
9. Select All Employees
10. Update Employee
11. Delete Employee
12. Insert Surgery Item
13. Insert Tools
14. Update Surgery Items
15. Update Surgery Items Part1
16. Update Surgery Items Part2
---


