# AssignNew


This guide will walk you through the process of setting up this project from a ZIP file. The steps include unzipping the project, installing dependencies, and running the development server.

Steps:
1. Unzip the Project:
   . Extract the contents of the ZIP file to a desired location on your computer. This will create a folder containing your Angular project files.

3. Navigate to the Project Directory:
  . Open your terminal or command prompt.
  .Use the cd command to navigate to the root directory of your unzipped Angular project.

Command:
  cd path_to_your_unzipped_project_folder

3.Install Dependencies:
  .Angular projects rely on various dependencies, which are listed in the package.json file. To install these dependencies, use the npm install command.
  
Command:
  npm install
  
This command will download and install all the necessary packages, creating a node_modules folder in your project directory.

4. Start the Development Server:
   .Once the dependencies are installed, you can start the Angular development server using the ng serve command. This will compile the project and serve it locally, making it accessible in your         browser.
   
Command:
  ng serve
  If you want to specify a port, you can use the --port option. For example:

Command:
ng serve --port 4200
After running this command, the terminal will display the URL where your Angular application is running (typically http://localhost:4200). Open this URL in your browser to see the app in action.
