# Admission_Enquiry_Form

## Date:07/07/2025

## Objective:

To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:

#### 1. Set Up the HTML Structure:

Use `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags to define the document structure.
Set the `<title>` as "Admission Enquiry Form".

#### 2. Add a Page Heading:

Use `<h1>` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:

Use the `<form>` tag to wrap all input elements. Set method="post" for structure.

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
    <title>Saveetha Engineering College - Admission Enquiry</title>
</head>
<body>
    <h1>Admission Enquiry Form</h1>
    <form action="testapi.js" method="post">
        <label for="name">Full Name:</label>
        <input type="text" name="name" placeholder="Enter Your Name">
        <br>
        <label for="e-mail">Email Address:</label>
        <input type="email" name="e-mail" placeholder="Enter your Email">
        <br>
        <label for="ph-no">Phone Number:</label>
        <input type="number" maxlength="10" name="ph-no" placeholder="Enter your Phone Number">
        <br>
        <label for="program">Program</label>

        <select name="program" id="pg">
            <option value="default" selected="true">Choose your Program</option>
            <option value="aids">AIDS</option>
            <option value="aiml">AIML</option>
            <option value="cse">CSE</option>
            <option value="it">IT</option>
        </select>
        <br>
        <label for="state">State</label>
        <input type="text" placeholder="Enter your State" name="state">
        <br>
        <label for="city">City</label>
        <input type="text" name="city" placeholder="City">
        <br>
        <label for="message">message</label>
        <br>
        <textarea name="message" id="10" cols="30"></textarea>
        <br>
        <button type="reset">reset Here</button>
        <button type="submit">Submit Here</button>

    </form>
</body>
</html>
```

## Output:

![image](./image.png)

## Result:

An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
