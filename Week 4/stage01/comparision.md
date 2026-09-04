PART B

Limitations by comparing both the programs

1. Repeated code for each appointment: the basic version needs a separate group of variables and print() statement for every appointment. For example, adding another patient requires copying the same code again. In comparison, the enhanced version can simply call book_appointment() again, making it easier to add more appointments.


2. No shared data structure: in the basic version, details such as patient1_name, practitioner1_name and appointment1_time are stored as separate variables. In comparison, the enhanced version groups these details into one dictionary for each appointment making the data easier to manage.


3. No central appointment list: the basic version does not store all appointments together and only prints them individually. In comparison, the enhanced version uses an appointments list to store every booking, allowing them to be searched, counted, or displayed later.


4. No reusable logic: the basic version requires the same print() statement to be written again for each appointment. In comparison, the enhanced version uses display_appointments() once and can use it for any number of appointments.


5. No validation: the basic version accepts empty patient names without checking. In comparison, the enhanced version uses ValueError to detect an empty patient_name, helping prevent basic data entry mistakes.
