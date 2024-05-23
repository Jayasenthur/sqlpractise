Welcome to the sql practice
Question type : Easy
1. Show first name of patients that start with the letter 'C'
SELECT first_name FROM patients where first_name like 'c%'

2. Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)
SELECT first_name, last_name FROM patients where weight between 100 and 120

3. Update the patients table for the allergies column. If the patient's allergies is null then replace it with 'NKA'
update patients set allergies='NKA' WHERE allergies IS NULL
