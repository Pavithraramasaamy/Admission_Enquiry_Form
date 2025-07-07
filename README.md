# Admission_Enquiry_Form
## Date:07-07-2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Enquiry Form</title>
</head>
<body>
    <h1>Admission Enquiry</h1>

        <label>Name:</label>
        <input type="text" placeholder="Enter Full Name" required>
        <br>

        <label>Email:</label>
        <input type="email" placeholder="Enter Email Address">
        <br>    

        <label>Phone No:</label>
        <input type="tel" placeholder="Enter Phone Number">
        <br>    

        <label>Gender</label><br>
        <input type="radio" name="gender" value="Male"> Male<br>
        <input type="radio" name="gender" value="Female"> Female<br>
        <input type="radio" name="gender" value="Other"> Other<br><br>

        <label>Date of Birth</label>
        <input type="date">
        <br>

        <label>Departments</label>
        <select>
            <option value="CSE">Computer Science and Engineering</option>
            <option value="AIDS">Artificial Intelligence and Data Science</option>
            <option value="AIML">Artificial Intelligence and Machine Learning</option>
            <option value="Select" selected="true">Select</option>
        </select>
        <br>

        <label>Academic Qualification</label>
        <textarea cols="30" rows="3"></textarea>
        <br>

        <label>Address</label>
        <textarea cols="30" rows="3"></textarea>
        <br>


        <input type="submit" value="Submit">
        <input type="reset" value="Reset">

</body>
</html>

```

## Output:

![image](https://github.com/user-attachments/assets/a5bc7f28-fe70-4d9f-b420-5275d123480e)



## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
