# Password_Manager-Intermidiate-
The provided Python script serves as a basic password manager that enables users to add new passwords or view existing ones.

    view Function:
        This function reads from a file named passwords.txt and displays the stored usernames and passwords.
        It opens the file in read mode ('r'), iterates through each line, splits the line into username and password using the '|' delimiter, and prints them.

    add Function:
        This function prompts the user to input an account name and password.
        It then appends the provided account name and password to the passwords.txt file, separated by the '|' delimiter.

    Main Loop:
        The script enters a while loop, prompting the user to choose between adding a new password, viewing existing passwords, or quitting.
        If the user chooses to add a password, the add function is called.
        If the user chooses to view passwords, the view function is called to display the existing passwords.
        If the user enters 'q', the loop breaks, and the program exits.
        If the user enters an invalid mode, an error message is displayed.

    Master Password:
        The script prompts the user to enter a master password at the beginning, but it doesn't appear to use this password for any authentication or encryption purposes.
