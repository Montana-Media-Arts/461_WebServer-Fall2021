---
title: Access HTML Forms
module: 4
jotted: true
---

<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Overview')">Overview</button>
  <button class="tablinks" onclick="openTab(event, 'Create')">Create a HTML Form</button>
 <button class="tablinks" onclick="openTab(event, 'Display')">Questions</button>
 <button class="tablinks" onclick="openTab(event, 'BasicForm')">Basic Form</button>
 
 
</div>

<div id="Overview" class="tabcontent" style="display:block">
PHP and HTML Forms
<p>
Keep in mind that PHP uses regular HTML forms.  There is no code behind, but we can still access the data.</p>
</div>

<div id="Create" class="tabcontent">
Create HTML Form
<p>
How do we create a basic input form?</p>
<p>
How do we send data to the PHP code?</p>
<p>
What role does method and action play?</p>
</div>

<div id="Display" class="tabcontent">
Access Data with PHP
<p>
How do we display the data entered?</p>
<p>
What is the difference between $_GET and $_POST?</p>
</div>
<div id="BasicForm" class="tabcontent">
Let's start with a basic form

<html>
    <head>
        <title>Login!</title>
    </head>
    <body>
        <form action="processlogin.php" method="POST">
        <table>
            <tr>
                <td>
                    Username:
                </td>
                <td>
                    <input type="text" name="username">
                </td>
            </tr>
            <tr>
                <td>
                    Password:
                </td>
                <td>
                    <input type="text" name="pwd">
                </td>
            </tr>
            <tr>
                <td colspan="2">
                    <input type="submit" value="Submit">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
</div>
