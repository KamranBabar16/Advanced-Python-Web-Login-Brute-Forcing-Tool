# Advanced-Python-Web-Login-Brute-Forcing-Tool

## This code DOES NOT promote or encourage any illegal activities! The content in this document is provided solely for educational purposes and to create awareness!


The Python tool presented here is an advanced web application brute force tool for logging into a website. It includes functionality to bypass CSRF token protection. This tool utilizes the requests library to send HTTP requests, BeautifulSoup for parsing HTML content, and the sys and os modules for handling system operations.

The tool prompts the user to enter the URL of the target web application or provides a default URL. It then loads a list of passwords from a file and specifies a list of usernames to try. The tool iterates through the combinations of usernames and passwords, attempting to log in to the web application.

For each iteration, it retrieves the CSRF token from the login form and constructs a POST request with the username, password, and CSRF token. It sends the request and checks the response to determine if the login was successful. If a successful login is detected, the tool displays the credentials and terminates.

To enable resumable brute force attacks, the tool includes functionality to save and load checkpoints. If the program is interrupted, it saves the progress, allowing it to resume from the last attempted password for each username. The checkpoints are stored in separate files for each username.

Overall, this Python tool provides an advanced and customizable way to automate the process of brute forcing web application login forms, with the additional capability to bypass CSRF token protection.


