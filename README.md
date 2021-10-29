# Hospital Management Database(CLI)

## Team members
<a href = "https://github.com/jeopardy1234">Yash Bhatia</a>  

<a href = "https://github.com/chandan-shrivastava">Chandan Shrivastava</a>   

<a href = "https://github.com/Nash2829">Nachiket Patil</a> 

## Installation

- Setup and enable MySQL server

```
sudo apt-get update
sudo apt-get install mysql-server
sudo mysql_secure_installation utility
sudo systemctl start mysql
```

- Login as root user using `sudo mysql -u root -p`, and make a new user connected to localhost

  ```sql
  CREATE USER 'enter_username_here'@'localhost' IDENTIFIED BY 'enter_password_here';
  GRANT ALL PRIVILEGES ON * . * TO 'enter_username_here'@'localhost';
  FLUSH PRIVILEGES;
  ```

  

- Run the python code

```
python3 Hospital-Management/Phase\ 4/Hospital.py 
```

- Enter your login details. You are ready to go now!!

## Supported Functionalities:

- **Insertion:**
  - `insertPatient()`
  - `insertAttendant()`
  - `insertMedicine()`
  - `insertEmployee()`
  - `insertBill()`
  - `insertRoom()`
- **Deletion:**
  - `deletePatient()`
  - `deleteAttendant()`
  - `deleteMedicine()`
  - `deleteEmployee()`
  - `deleteBill()`
  - `deleteRoom()`
- **Modification:**
  - `updatePatient()`
  - `updateAttendant()`
  - `updateMedicine()`
  - `updateEmployee()`
  - `updateBill()`
  - `updateRoom()`
- **Report:**
  - `GeneratePatientReport()`
  - `GenerateDoctorReport()`
- **Additional:**
  - `GetMedicineByPartialName()`
  - `GetMedicineByMincost()`

<hr>

This is a part of Data and Applications project @IIITH

