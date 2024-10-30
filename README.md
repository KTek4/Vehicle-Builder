# Vehicle-Builder

## Updating Existing Code

The code provided in this project has been properly updated to allow for additional functionality from trucks and motorcycles. The project prompts the user to create a new vehicle or select an existing vehicle. After going through the creation process or the selection process, the user is able to perform certain actions with the selected vehicle. The user is returned to the actions menu after each action until they decide to exit the project.

### User Story

```md
AS a developer
I WANT to update an existing application to include additional vehicle types
SO THAT I am able to comprehend and work with existing code bases.
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input

WHEN I am prompted to create a new vehicle or existing vehicle
THEN I can choose between the two options

WHEN I am prompted to choose the vehicle type during creation
THEN I can choose between car, truck, and motorbike

WHEN I am prompted for details about the vehicle
THEN I can enter the vehicle information

WHEN I have entered all the vehicle information
THEN I can use the created vehicle

WHEN I select an existing vehicle
THEN I can use the selected existing vehicle

WHEN I have created a new vehicle or selected an existing vehicle
THEN I can perform actions with that vehicle

WHEN I perform an action with a vehicle
THEN I see the result of the action in the command-line

WHEN I complete the process of performing an action
THEN I can perform additional actions until I choose to exit
```
## Instructions to Run the Code

In the terminal, navigate to the src folder in Vehicle Builder
The program will need to be initiated by typing in:
```md
npm run start
```

Following this, the user will be guided through a set of questions.

### DIY Vehicle
First, Select a prebuilt vehicle or create their own
If the user chooses to build their own, the following set of questions and prompts will continue

Second, Select either a Car, Truck, or Motorbike
Third, Input the Color, Make, Model, Weight, and, Top Speed.
If it applies the user will also need to input the Towing Capacity.

Afterwards, we can move on to the Actions that can be performed on the vehicle

### Prebuilt Vehicle
If the user decides instead to use a prebuilt vehicle, the questions will instead start with the actions that can be applied to the chosen vehicle

### Walkthrough Video
For additional functionality or to see how the program operates see the [Walkthrough Video](https://youtu.be/RpxYXoaEcog) linked here.