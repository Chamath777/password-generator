# 03 JavaScript: Password Generator

## Task

 By modifying given starter code to create an application that enables employees to generate random passwords based on criteria that they’ve selected. This app will run in the browser and will feature dynamically updated HTML and CSS powered by JavaScript code that written. It has a clean and polished, responsive user interface that adapts to multiple screen sizes.

The password can include special characters. If you’re unfamiliar with these, see this [list of password special characters](https://www.owasp.org/index.php/Password_special_characters) from the OWASP Foundation.

## User Story

```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security
```

## Acceptance Criteria

```
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```


## Appearance and functionality:

- The Password Generator application displays a red button to "Generate Password"

![The Password Generator application displays a red button to "Generate Password".](./Assets/images/home.png)

- User to choose number of characters as desired. 

![User to choose number of characters as desired. ](./Assets/images/character.png)

- Prompt option that user to choose numerics if required.

![Prompt option that user to choose numerics if required](./Assets/images/numbers.png)

- Prompt that user to choose lower case letters if required.

![Prompt that user to choose lower case letters if required.](./Assets/images/lowercase.png)

- Prompt that user to choose upper case letters if required.

![Prompt that user to choose upper case letters if required.](./Assets/images/uppercase.png)

- Prompt that user to choose special characters if required.

![Prompt that user to choose special characters if required.](./Assets/images/special.png)

- Finally, the passowrd generated screen for the user.

![Finally, the passowrd generated screen for the user.](./Assets/images/password.png)

- If user made a mistake the screen propmts to start the process of re-entering criterias.

![If user made a mistake the screen propmts to start the process of re-entering criterias.](./Assets/images/re-select.png)