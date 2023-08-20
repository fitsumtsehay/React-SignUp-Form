# Building a sign-up form using React
![signup](https://github.com/fitsumtsehay/React-SignUp-Form/assets/63597726/bb205c27-5e1c-431c-8af7-77a741382e9a)
## Steps
### Step 1
Open the App.js file. Convert all the elements from the form to controlled components by adding the value and onChange attributes to each input. Make sure the password input is obscured.

### Step 2
Show an error message if the password is less than 8 characters long and the user has interacted with the input at least once. The error message should be displayed below the password input
### Step 3
Prevent the default behaviour of the form when the user clicks the submit button.

### Step 4
Implement the body of getIsFormValid function to return true if the form is valid and false otherwise. This determines the submit button state. The rules for the form to be valid are as follows:
The first name cannot be empty.
The email must be a valid email address and can't be empty. A function called validateEmail has already been provided for you to check if the email is valid. It returns true if the email is valid, otherwise  false is returned.
The password must be at least 8 characters long.
The role must be either individual or business.

### Step 5
Implement the body of clearForm function to clear the form state after a successful submission.
