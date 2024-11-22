# Random-Password-Generator

#### Description:
This Python script generates a strong, random password with a mix of uppercase and lowercase letters, digits, and punctuation marks. The user is prompted to enter the desired length of the password, with a minimum requirement of 8 characters. The password is then generated with 60% letters (both uppercase and lowercase) and 40% digits and special characters. It shuffles and combines these elements to ensure a strong password.

#### Code Explanation:
1. **Importing Modules**: 
   - The `string` module is used to get predefined character sets like lowercase letters, uppercase letters, digits, and punctuation.
   - The `random` module is used to shuffle lists and generate random choices.

2. **Character Sets**:
   - `s1` contains lowercase letters.
   - `s2` contains uppercase letters.
   - `s3` contains digits.
   - `s4` contains punctuation marks.

3. **User Input**:
   - The script asks the user for the desired password length and ensures that it's at least 8 characters long.

4. **Password Generation Logic**:
   - The script calculates how much of the password should consist of letters, digits, and punctuation.
   - The password consists of 30% lowercase letters, 30% uppercase letters, and 20% each of digits and punctuation.
   - These sets are shuffled and combined to form the final password.

5. **Output**:
   - The script prints the generated strong password.

---

### Usage:

1. **Clone the repository**:
   Clone this repository to your local machine using Git:

   ```bash
   git clone https://github.com/yourusername/random-password-generator.git
   cd random-password-generator
   ```

2. **Run the Script**:
   Open your terminal or command prompt and run the Python script:

   ```bash
   python password_generator.py
   ```

3. **Enter the Desired Password Length**:
   When prompted, enter the number of characters you want in your password (must be at least 8).

   Example:

   ```text
   How many characters do you want in your password? 12
   ```

4. **Generated Password**:
   The script will generate and display a strong password on the screen.

   Example output:

   ```text
   Strong Password: Nmb#qL%8zJ@c
   ```

---

### Screenshot:

Below is an example of how the script works:

1. **Initial Prompt**:
   <img width="301" alt="{676F4A41-753B-4DDC-9A08-F75B12857E54}" src="https://github.com/user-attachments/assets/2f4e5b52-63b2-46b5-b40a-e0655b8d82cf">


2. **Generated Password Output**:
   <img width="289" alt="{8A4B28B2-E329-4F21-A667-381A9F3F79D3}" src="https://github.com/user-attachments/assets/889bacfe-7109-4190-af9e-e2bca15db182">


