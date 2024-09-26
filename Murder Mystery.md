SELECT * 
FROM crime_scene_report
LIMIT 5;
![image](https://github.com/user-attachments/assets/410c402d-a2ef-4bab-8e9e-05ee7e81355a)
SELECT *
FROM crime_scene_report
WHERE type = "murder";
SELECT *
FROM crime_scene_report
WHERE type = "murder"
AND date = 20180115
AND city = "SQL City";
![image](https://github.com/user-attachments/assets/3c8582c1-1a70-42d5-bbd2-9f7f112e95ab)
SELECT *
FROM person
LIMIT 5;
![image](https://github.com/user-attachments/assets/28b274f9-1ca1-438c-acd5-09cf3436d818)
SELECT *
FROM person
WHERE address_street_name = "Northwestern Dr"
ORDER BY address_number DESC;
![image](https://github.com/user-attachments/assets/55a7031e-7439-4b7c-b110-c9b00486af55)
SELECT *
FROM person
WHERE name LIKE '%Annabel%'
AND address_street_name = "Franklin Ave";
![image](https://github.com/user-attachments/assets/2043642d-205d-4052-afa6-3aef8aaa2b4f)
SELECT *
FROM interview
WHERE person_id IN ("14887", "16371");
![image](https://github.com/user-attachments/assets/d2ca29dd-9d37-4f8d-ab41-020034d54bd2)
SELECT *
FROM get_fit_now_check_in
WHERE membership_id LIKE '48Z%'
AND check_in_date = "20180109";
![image](https://github.com/user-attachments/assets/cb94640a-da60-4bd4-9dbb-b478f6f18972)
SELECT *
FROM drivers_license
WHERE gender = "male"
AND plate_number LIKE '%H42W%';
![image](https://github.com/user-attachments/assets/dcdb1c87-51f8-4cc7-99a4-5c96159634c9)
SELECT *
FROM person
WHERE license_id IN ("423327", "664760");
![image](https://github.com/user-attachments/assets/2d09b1c3-c655-4a4e-ab84-a42055bafdb6)
SELECT *
FROM get_fit_now_member
WHERE person_id IN ("51739", "67318");
![image](https://github.com/user-attachments/assets/b9fe9e89-8fe5-4d89-8e54-2a777d671e08)
![image](https://github.com/user-attachments/assets/51b3c360-116a-4697-b66e-8e9067f5c00e)



