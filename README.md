# PasswordGenerator

# Synopsis
This is a random password generator that generates an output based on user defined inputs. The end password generated is between 8 and 128 characters in length. This program is built using Javascript (event listener to listen to button click, functions, arrays, for loop, if statemetns and math random and math floor functions. 

# User Story
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security


# Screenshot 
<img width="769" alt="Screen Shot 2020-02-11 at 8 44 16 AM" src="https://user-images.githubusercontent.com/56641651/74241794-ba2ec500-4caa-11ea-9221-ee0a7684e86b.png">

# Acceptance Criteria 
The password generator fulfills the below acceptance criteria: 

* A button initiates the password generation process
* A series of prompts asks a user for password criteria
* User is able to select which criteria to include in the password
* Length of the generated password is between 8 - 128 characters
* User is able to choose lowercase, uppercase, numeric, and/or special characters with each prompt 
* All user input is validated
* The resultant password mataches the user criteria 
* The resultant password is written to the page 

# Sample Code


    getLowerCases: function() {
      return String.fromCharCode(Math.floor(Math.random() * 26 + 97));
    },

    getUpperCases: function() {
      return String.fromCharCode(Math.floor(Math.random() * 26 + 65));
    },

    getSpecialCharacters: function() {
      return specialCharacters[Math.floor(Math.random() * specialCharacters.length)]
 
  
  
 # Installation
To use this portfolio, log into your GitHub account (if you don’t have a GitHub user profile, create one at https://github.com/join) and open this link in your browser: https://github.com/natashagils/PasswordGenerator. Then click on the "Fork" button at the top right corner and wait until the repo is forked. 



