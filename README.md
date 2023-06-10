# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```

# OUTPUT
![Screenshot 2023-06-11 011242](https://github.com/ShiyamKumaran/Ex06_Web-Design/assets/127816458/d5bc2b36-5630-462d-994c-89d584789461)
![Screenshot 2023-06-11 011431](https://github.com/ShiyamKumaran/Ex06_Web-Design/assets/127816458/bd8bb1cb-54f6-4476-ac19-e4d01498bf4a)
![Screenshot 2023-06-11 011508](https://github.com/ShiyamKumaran/Ex06_Web-Design/assets/127816458/9154778a-9505-4617-9929-05aad09239e1)
![Screenshot 2023-06-11 011554](https://github.com/ShiyamKumaran/Ex06_Web-Design/assets/127816458/d980011f-4990-40f7-bc2c-0d840dcaaf93)
![Screenshot 2023-06-11 011624](https://github.com/ShiyamKumaran/Ex06_Web-Design/assets/127816458/7f5d4bd2-c721-4a6c-b8ac-7d8a69cb9f4f)
























## RESULT

  Student result using JavaScript is created successfully.
