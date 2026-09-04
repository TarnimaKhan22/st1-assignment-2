PART C
AI as tutor

1. What the code does?

Ans: The function book_appointment creates a simple in‑memory appointment record using a Python dictionary and stores it inside the global appointments list.
Step‑by‑step:

    1) The program starts with an empty list named appointments.

    2) When book_appointment() is called: It checks that patient_name is not empty, It creates a dictionary containing: "patient", "practitioner" and "time", It appends that dictionary to the global appointments list.

    3) display_appointments() loops through the list and prints each stored appointment.

    4) At the bottom, two example appointments are added and then displayed.

This is a classic beginner‑friendly use of lists, dictionaries, and functions.


2. Three limitations
    1) No duplicate checking — The system allows booking the same patient, practitioner, or time multiple times without warning.

    2) No validation of time format — The appointment time is treated as plain text, so invalid or inconsistent formats can slip in.

   3) No ability to search or cancel — Once stored, appointments can only be displayed; there is no way to find, update, or remove them.


3. Suggested improvements

These stay within your requirement of not rewriting the whole application:

    1) Add a search function to find appointments by patient or practitioner.

    2) Add basic time validation using datetime.strptime() to ensure consistent formatting.

    3) Add a cancel_appointment function that removes a matching dictionary from the list.

    4) Add a simple duplicate check before appending to the list.


4. Two questions to test your understanding

Q. Why is using a list of dictionaries a good structure for storing multiple appointments?

Ans: Each dictionary holds one appointment's fields (patient, practitioner, time) with named keys, so it's clear and easy to read. The list lets you store as many appointments as needed and loop through them easily.

Q. What would happen if you removed the if not patient_name: check from book_appointment()?

Ans: The function would accept a blank or none patient name without error. It would get added to the list and printed as a real appointment.