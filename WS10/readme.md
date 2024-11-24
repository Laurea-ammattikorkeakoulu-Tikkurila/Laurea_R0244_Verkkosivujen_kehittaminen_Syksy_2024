# HTML Forms and Tables Learning Exercise

## Overview

This exercise is designed to help you learn and practice creating HTML forms and tables. You will learn how to structure forms, use various input types, and create tables to display data effectively.

## Objectives

- Understand the structure of HTML forms
- Learn how to use different form elements (input, select, textarea, etc.)
- Implement form validation
- Create and style HTML tables
- Use CSS to enhance the appearance of forms and tables

## Instructions

### Forms

1. Create a form with the following elements:
   - Text input for first name
   - Text input for last name
   - Email input
   - Password input
   - Checkbox for subscribing to a newsletter
   - Radio buttons for selecting gender
   - Dropdown menu for selecting a country
   - Textarea for additional comments
   - Submit button

2. Add form validation to ensure all required fields are filled out correctly.

3. Style the form using CSS to make it visually appealing.

### Tables

1. Create a table to display a list of users with the following columns:
   - First Name
   - Last Name
   - Email
   - Gender
   - Country

2. Add at least 5 rows of sample data to the table.

3. Style the table using CSS to improve readability and appearance.

## Example Code

### Form Example

```html
<form>
  <label for="firstName">First Name:</label>
  <input type="text" id="firstName" name="firstName" required>

  <label for="lastName">Last Name:</label>
  <input type="text" id="lastName" name="lastName" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <label for="newsletter">Subscribe to Newsletter:</label>
  <input type="checkbox" id="newsletter" name="newsletter">

  <label>Gender:</label>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label>

  <label for="country">Country:</label>
  <select id="country" name="country">
    <option value="usa">USA</option>
    <option value="canada">Canada</option>
    <option value="uk">UK</option>
  </select>

  <label for="comments">Comments:</label>
  <textarea id="comments" name="comments"></textarea>

  <button type="submit">Submit</button>
</form>