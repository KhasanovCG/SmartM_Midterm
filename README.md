# SmartM_Midterm
Project Report: Fleet Management System
Project Overview:
The Fleet Management System is a ROS2-based application designed to manage and route a fleet of vehicles. The system allows users to allocate and route vehicles based on their specified fleet size. The project consists of several components, including defining a ROS2 Action, implementing an Action Server, creating an Action Client CLI, developing a professional CLI, testing with scenarios, and documentation.

Task 1: Define ROS2 Action
A ROS2 Action file named fleet_management.action has been created. This action file defines the structure of the fleet management action, including the Action Goal, Result, and Feedback messages. The Action Goal includes an integer field for the fleet size, the Action Result includes an array of strings for vehicle routes, and the Action Feedback includes a float for the completion percentage.
Task 2: Implement the Action Server
A Python script named fleet_management_server_cli.py has been implemented to serve as the Action Server.
The server receives fleet size requests, performs fleet management logic (e.g., allocation and routing), and returns calculated routes as the Action Result.
Proper error handling and logging have been implemented to ensure robust server functionality.
Task 3: Implement the Action Client CLI
A Python script named fleet_management_client_cli.py has been developed to act as the Action Client.
This client allows users to request fleet management tasks by specifying the fleet size.
It sends the request to the server, receives the routes in response, and displays them to the user.
Task 4: Create a Professional CLI
A professional Command Line Interface (CLI) has been designed using the click library.
The CLI provides an option for users to allocate and route vehicles by specifying the fleet size.
The professional CLI internally calls the Action Client CLI to perform the task, enhancing the user experience.
Task 5: Testing with Scenarios
Two detailed testing scenarios have been created, each with a goal description, fleet size, and expected output (vehicle routes).
These scenarios are intended to verify the functionality of the fleet management system under various conditions.

The Fleet Management System project has successfully defined a custom ROS2 Action, implemented an Action Server and Client, created a professional CLI, and provided thorough documentation. The application is ready for testing with the provided scenarios, and the documentation ensures that users can set up and utilize the system effectively. This project represents a robust solution for managing and routing fleets in a ROS2 environment.
