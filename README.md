# Vehicle Builder

## Description

The Vehicle Builder is a command-line application that allows users to create and manage vehicles. Users can choose to create a new vehicle (Car, Truck, or Motorbike), select an existing vehicle, and perform actions with it. The application demonstrates how to work with classes, user input, and menus in Node.js.

## Features

Create Vehicles: Users can create vehicles by selecting the type and providing details such as make, model, and year.

Select Existing Vehicles: Choose a previously created vehicle from a list.

Perform Actions: Perform actions like honking or displaying the vehicle's information.

Interactive Menu: A user-friendly menu system guides the user through all operations.

## Installation

1. Clone the repository:

   - git clone <repository-url>

2. Navigate to the project directory:

    - cd vehicle-builder

3. Install dependencies:

    - npm install

## Usage

1. Start the application:

    - npm start

2. Follow the prompts:

    - Select an option to create a vehicle, select an existing vehicle, or exit the application.

    - If creating a vehicle, provide the make, model, and year.

    - Select a vehicle to perform actions like start vehicle, accelerate, decelerate, stop vehicle, turn, wheelie, tow or print details.

    - Exit the application when done.

## File Structure

vehicle-builder/
-- index.js          # Main application file
├── vehicle.js        # Vehicle class and subclasses
├── package.json      # Project metadata and dependencies
└── README.md         # Project documentation

## Technologies Used

  - Node.js: For the runtime environment.

  - Inquirer.js: For handling interactive user prompts in the command line.

## Walkthrough Video

A video walkthrough demonstrating the application’s functionality is available here.

## Future Enhancements

  - Add persistent storage to save vehicle data between sessions.

  - Introduce additional vehicle types with unique features.

  - Implement more actions specific to each vehicle type.

## License

This project is licensed under the MIT License.
