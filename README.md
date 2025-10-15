<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lab 5 Form</title>
</head>
<body>
  <h2>Lab 5 Form</h2>

  <form action="http://bloomingdale.sat.iit.edu/kriedan/lab3formscript.php" method="post">
    <!-- First Name -->
    <label for="first_name_field">First Name:</label>
    <input type="text" id="first_name_field" name="first_name_field" required><br><br>

    <!-- Last Name -->
    <label for="last_name_field">Last Name:</label>
    <input type="text" id="last_name_field" name="last_name_field" required><br><br>

    <!-- Phone Number -->
    <label for="phone_field">Phone:</label>
    <input type="text" id="phone_field" name="phone_field" required><br><br>

    <!-- Email -->
    <label for="email_field">Email:</label>
    <input type="email" id="email_field" name="email_field" required><br><br>

    <!-- Comments -->
    <label for="comments_field">Comments:</label><br>
    <textarea id="comments_field" name="comments_field" rows="4" cols="40"></textarea><br><br>

    <!-- Gender (Radio Buttons) -->
    <label>Gender:</label><br>
    <input type="radio" id="male" name="gender_field" value="Male">
    <label for="male">Male</label><br>

    <input type="radio" id="female" name="gender_field" value="Female">
    <label for="female">Female</label><br>

    <input type="radio" id="other" name="gender_field" value="Other">
    <label for="other">Other</label><br><br>

    <!-- Availability (Checkboxes) -->
    <label>Available Days:</label><br>
    <input type="checkbox" id="monday" name="available_field[]" value="Monday">
    <label for="monday">Monday</label><br>

    <input type="checkbox" id="tuesday" name="available_field[]" value="Tuesday">
    <label for="tuesday">Tuesday</label><br>

    <input type="checkbox" id="wednesday" name="available_field[]" value="Wednesday">
    <label for="wednesday">Wednesday</label><br>

    <input type="checkbox" id="thursday" name="available_field[]" value="Thursday">
    <label for="thursday">Thursday</label><br>

    <input type="checkbox" id="friday" name="available_field[]" value="Friday">
    <label for="friday">Friday</label><br><br>

    <!-- Age (Dropdown Menu) -->
    <label for="age_field">Age Range:</label>
    <select id="age_field" name="age_field">
      <option value="Under 18">Under 18</option>
      <option value="18-25">18-25</option>
      <option value="26-35">26-35</option>
      <option value="36-50">36-50</option>
      <option value="51+">51+</option>
    </select><br><br>

    <!-- Hidden Field -->
    <input type="hidden" name="hidden_field" value="Your Name Here">

    <!-- Submit Button -->
    <input type="submit" value="Submit">
  </form>
</body>
</html>

