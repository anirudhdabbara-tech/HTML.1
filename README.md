# HTML.1
I have learned html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        // creating an obeject
        let student={
            name:"Anirudh",
            Rollnu:68,
            course:"CSE326",
            detalis : function(){
                return (this.name+" ",this.rollno+" ",this.course)
            }

        }
        //access the property
        // 1. dot notation 2.bracket notation
        document.write(student.name+"<br>");
        document.write(student["course"])
        //adding a property
        student.branch="Btech CSE"
        document.write(student["branch"])
        //Delete a property
        delete student.Rollno;
        document.write(student.Rollno +"<br>")
    </script>
</body>
</html>
