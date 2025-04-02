# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table {
            border-collapse: collapse;
        }
    </style>
</head>

<body>
    <ol type="I">
        <li>Mango</li>
        <li>Apple</li>
        <li>Orange</li>
    </ol>

    <br>
    <img src="https://images.pexels.com/photos/30150599/pexels-photo-30150599/free-photo-of-thoughtful-woman-in-urban-black-and-white-scene.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
        width="200px" height="300px">
    <br>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Address</th>
            <th>Mobile</th>
        </tr>
        <tr>
            <td>Rush Musonza</td>
            <td>rushmm9@gmail.com</td>
            <td>99 Caithness Road,Harare</td>
            <td>0779121444</td>
        </tr>
        <tr>
            <td>Roshy Musonza</td>
            <td>musohtany@gmail.com</td>
            <td>95 Caithness Road,Harare</td>
            <td>0779121844</td>
        </tr>
        <tr>
            <td>Roash Musonza</td>
            <td>musyytany@gmail.com</td>
            <td>90 Caithness Road,Harare</td>
            <td>0779121464</td>
        </tr>
        <tr>
            <td>Rosh Mad</td>
            <td>mady@gmail.com</td>
            <td>9 Caithness Road,Harare</td>
            <td>0779121675</td>
        </tr>
        <tr>
            <td>Ryan Musonza</td>
            <td>ryanm@gmail.com</td>
            <td>98 Caithness Road,Harare</td>
            <td>0779122844</td>
        </tr>
    </table>
    <br>
    <fieldset>
        <legend>Registration Form</legend>
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Enter Name" required><br>
        <label for="email">Email:</label>
        <input type="text" id="email" placeholder="Enter Email" required><br>
        <label for="password">Password:</label>
        <input type="password" id="Email" placeholder="Enter Password" required><br><br>
        <label for="radio">Male</label>
        <input type="radio">
        <label for="radio">Female</label>
        <input type="radio"> <br><br>
        <caption>Select your country</caption>
        <select for="country">
            <option value="zim">Zimbabwe</option>
            <option value="sa">South Arica</option>
            <option value="nig">Nigeria</option>
            <option value="zam">Zambia</option>

        </select>
        <br>
        <label for="check">Check if you have filled the form</label>
        <input type="checkbox">


    </fieldset>


</body>

</html>
