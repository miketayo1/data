//This displays the list of students with abc along with their classes
SELECT stud_name.Students, teach_name 
FROM Students s, Teacher t
LEFT JOIN Class c on c.id_class= S.id_stud
LEFT JOIN c.id_class = T.id_teach
WHERE id_stud= "1"


//This sets the new value for the class and age wherever the class id is 
UPDATE Class.id_class, 
SET teach_class= "JSS3", teach_age =40
WHERE Class.id_teach = 22

//Deletes all the students with age greater than  16
DELETE from Students
WHERE stud_age >16


//Selects the id and class name of all students
SELECT id_class.Class, class_name.Class
from Class c, Teacher t
JOIN c.id_class = t.id_teach
ORDER BY stud_name DESC


// Gives the number of teachers whose age is below 50
SELECT COUNT (teach_subjects) 
FROM Teacher
WHERE teach_age < 50