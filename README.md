# grow-global-task
A simple web application. Task: Build a web application using React.js for the frontend and Node.js for the backend. Application Features: 1. The application should have a user registration and login system (with validation). 2. Users should be able to create, read, update, and delete posts once they log in. 


1. Clone the repository: Open your command line interface (CLI) or terminal and navigate to the directory where you want to clone the repository. Use the command "git clone <git url>", replacing "<git url>" with the actual URL of the repository. This will create a local copy of the repository on your machine.

2. Install dependencies: Once the repository is cloned, navigate to the project's root directory using the CLI. The project may have separate client and server applications, so you'll need to install the dependencies for both.

- For the server application: Use the command "npm install" to install the required npm packages specified in the server's package.json file. This will download and install the necessary dependencies.

- For the client application: Navigate to the client directory (if applicable) using the CLI, and again run the command "npm install" to install the required npm packages for the client application.

3. Start the server and client: After installing the dependencies, you can start the server and client applications.

- For the server application: In the server's root directory, run the command "npm start" or "node index.js" to start the server.

- For the client application: In the client directory (if applicable), run the command "npm start" to start the client application.

4. To add a `.env` file with two variables for the database URL and port number, follow these steps:

  1. Create a file named `.env` in the root directory of your project.

  2. Open the `.env` file using a text editor.

  3. Add the following lines to the `.env` file, replacing the placeholders with your actual values:

  ```
  DATABASE=your_database_url
  PORT=your_port_number
  ```

  4. Save the `.env` file.

  5. Make sure to add `.env` to your project's `.gitignore` file to prevent sensitive information from being committed to version control.

  6. In your server application code, you can access these environment variables using a library like `dotenv` or by manually reading the values from the `.env` file.



4. Access the web application: Once both the server and client applications are running, you should see a URL provided in the terminal or command line. Open your web browser and enter the provided URL to access the web application.

Here are some outputs of the application
1.Home
![Home](https://github.com/EU1182053/grow-global-task/assets/65112935/451af78f-3eae-4959-a38e-abcc0774570e)

2.signup
![signup](https://github.com/EU1182053/grow-global-task/assets/65112935/b217b161-90f8-4597-8c2f-b2a09f303606)


3.login
![login](https://github.com/EU1182053/grow-global-task/assets/65112935/b8c5da7e-ffc5-4344-b1e7-8804cd095194)

4.add task
![addtask](https://github.com/EU1182053/grow-global-task/assets/65112935/abcea851-0fcc-482a-af63-56e2a2d364a7)


5.edit task
![edit](https://github.com/EU1182053/grow-global-task/assets/65112935/a0be34b5-99c3-4c58-881d-6ef775315b42)

6.delete task
![editDelete](https://github.com/EU1182053/grow-global-task/assets/65112935/53d365bc-80c4-4420-9cf9-6bcdeeb820cb)



