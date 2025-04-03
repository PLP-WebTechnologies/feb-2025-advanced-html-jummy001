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

<DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index Page</title>
   
</head>
<body>
    <!-- Section: Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Manual Book</li>
            <li>Engine</li>
            <li>Adaptor</li>
           <li>Labtop</li>
        </ol>
    </section>

    <!-- Section: External Image from Pexels -->
    <section>
        <h2>External Image</h2>
    
        <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Beautiful Landscape" width="500">
    </section>

    <!-- Section: Table of 5 Contacts -->
    <section>
        <h2>Contacts</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St, City</td>
                    <td>+1234567890</td>
                    <td>john@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St, Town</td>
                    <td>+0987654321</td>
                    <td>jane@gmail.com</td>
                </tr>
                <tr>
                    <td>Bob Johnson</td>
                    <td>789 Maple Ave, Village</td>
                    <td>+1122334455</td>
                    <td>bob@gmail.com</td>
                </tr>
                <tr>
                    <td>Alice Williams</td>
                    <td>321 Oak Rd, Metropolis</td>
                    <td>+6677889900</td>
                    <td>alice@gmail.com</td>
                </tr>
                <tr>
                    <td>Charlie Brown</td>
                    <td>654 Pine Ln, Hamlet</td>
                    <td>+5566778899</td>
                    <td>charlie@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Section: Registration Form -->
    <section>
        <h2>Registration Form</h2>
        
            <div>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
            </div>
            <!-- Email Field -->
            <div>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>
            </div>
            <!-- Password Field -->
            <div>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required>
            </div>
            <!-- Date Field -->
            <div>
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>
            </div>
            <!-- Dropdown Field -->
            <div>
                <label for="country">Country:</label>
                <select id="country" name="country" required>
                    <option value="">Select your country</option>
                    <option value="usa">USA</option>
                    <option value="canada">Canada</option>
                    <option value="uk">UK</option>
                </select>
            </div>
            <!-- Radio Buttons for Gender -->
            <div>
                <p>Gender:</p>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label>
                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label>
            </div>
            <!-- Checkboxes for Interests -->
            <div>
                <p>Interests:</p>
                <input type="checkbox" id="sports" name="interests" value="sports">
                <label for="sports">Sports</label>
                <input type="checkbox" id="music" name="interests" value="music">
                <label for="music">Music</label>
                <input type="checkbox" id="travel" name="interests" value="travel">
                <label for="travel">Travel</label>
            </div>
            <!-- Submit Button -->
            <div>
                <button type="submit">Register</button>
            </div>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;          
          background-color: 	#F08080;
   }
        /* Styling for the table */
        table {
            border-collapse: collapse;
            width: 100%;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
        }
        th {
            background-color: #f2f2f2;
        }
        /* Form element spacing */
        form > div {
            margin-bottom: 15px;
        }
        label {
            display: inline-block;
            width: 120px;
        }
    Link to my Assignment:https://codepen.io/jummy001/pen/KwKbOEB
        </form>
    </section>
</body>
</html>
**THE STYLES** CSS

