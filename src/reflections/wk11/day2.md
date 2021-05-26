Day2 

Afternoon Challenge https://github.com/Melia88/contractor

Read Dotnet WebAPI's > Relationships, and answer the following questions

What is the difference between a primary key and a foreign key
> A primary key is the unique identifier of the table itself and a foreign key is a key from another table that we are using.

What is an Alias?
> An alias is a name we are defining in our sql statement to call upon when needed.

Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors_patients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
>

 SELECT 
    d.*,
    p.*
    dp.Id as doctorsPatientsId
    dp.doctorId as doctorId,
    dp.patientId as patientId
  FROM 
    doctors_patients dp
    JOIN doctors d ON d.id = dp.doctorId
    JOIN patients p ON p.id = dp.patientId
  WHERE doctorId = @id;
 