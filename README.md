<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Form</title>
  <link rel="stylesheet" href="form.css" />
</head>

<body>
  <div class="wrapper">
    <div class="margin-container">

      <img src="Logo.png">
      <h1>For Individuals</h1>

      <p>
        Start benefiting from the wellness experience. For companies look on
        in increase productivity, and improving organization wellness.
      </p>
    </div>

    <div class="form-wrapper">
      <div class="input-group">
        <div>
          <label id="firstname">First Name</label><br />
          <input type="text" placeholder="Tolu" />
        </div>

        <div>
          <label id="lastname">Last Name</label><br />
          <input type="text" />
        </div>
      </div>

      <div class="input-group">
        <div>
          <label id="gender">Gender</label><br />
          <select id="gender" name="gender" required>
            <option disabled selected value="Select gender">
              Select gender
            </option>
            <option value="Male">Male</option>
            <option value="Female">Female</option>
            <option value="Other">Other</option>
          </select>
        </div>

        <div>
          <label for="dob">Date of Birth</label><br />
          <input type="date" id="dob" name="dob" />
        </div>
      </div>

      <div class="input-group">
        <div>
          <label for="weight">Weight(KG)</label><br />
          <input type="text" placeholder="Enter Weight" />
        </div>

        <div>
          <label for="height">Height(CM)</label><br />
          <input type="text" placeholder="Enter height here" />
        </div>
      </div>

      <div>
        <label for="height">Activity Level</label><br />
        <select id="gender" name="gender" required>
          <option value="Select gender">Select here</option>
        </select>
      </div>

      <div>
        <label for="height">Password</label><br />
        <input type="password" />
        <i class="fa fa-eye" aria-hidden="true"></i>
      </div>

      <div>
        <input type="button" value="Register" class="register-button">
      </div>

      <p>By clicking Register, you agree to our <a href="Terms of Use">Terms of Use</a> and our <a
          href="Privacy Policy">Privacy Policy</a> </p>
    </div>
  </div>
</body>

</html>
