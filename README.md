#OIBSIP_Password Generator:
This project is a simple Password Generator that allows users to create strong, random passwords based on custom criteria such as length, and the inclusion of uppercase letters, digits, and special characters.

#How It Works:
**User Input**:

The program welcomes the user and prompts them to specify the desired length of the password.
Users can also choose whether to include uppercase letters, digits, and special characters by entering “y” (yes) or “n” (no) for each option.
**Main Functionalities**:

1. **Password Generation**: Creates a password by randomly selecting characters from a pool based on the user’s choices.
2. Character Pool Customization: Builds a character pool containing lowercase letters by default, with optional inclusion of uppercase letters, numbers, and special characters based on user input.
3. Validation: Checks if the user input meets criteria (e.g., length) and handles invalid inputs gracefully.
**Error Handling**:

If the user enters invalid data (e.g., a non-integer for the password length), the program displays an error message and prompts the user again.
**Code Overview**:
**Functions**:
generate_password(length, use_uppercase, use_digits, use_special): Generates a password using the specified length and character pool. Builds the pool based on user selections and returns a randomly generated password.
**Main Program**:
The main() function initiates the program, gathers input, and displays the generated password.
Handles invalid input with an error message, ensuring a smooth user experience.
