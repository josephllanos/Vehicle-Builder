# Vehicle-Builder

## Description

The Vehicle Builder is a command-line application that allows users to create and manage different types of vehicles, including cars, trucks, and motorbikes. Users can perform various actions on these vehicles, such as starting, accelerating, decelerating, and performing unique actions like towing (for trucks) or wheelies (for motorbikes).

## Features

- Create vehicles of type **Car**, **Truck**, or **Motorbike**.
- Perform actions such as:
  - Start, accelerate, decelerate, stop, turn, and reverse.
  - Tow other vehicles (Truck-specific).
  - Perform wheelies (Motorbike-specific).
- View detailed information about each vehicle.
- Manage multiple vehicles in a single session.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Develop
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   npm run build
   ```

## Usage

Run the application using the following command:
```bash
npm start
```

### Workflow

1. **Choose an Option**:
   - Create a new vehicle.
   - Select an existing vehicle.

2. **Create a Vehicle**:
   - Choose the type of vehicle: Car, Truck, or Motorbike.
   - Enter the required details for the selected vehicle type.

3. **Perform Actions**:
   - Select a vehicle and perform actions such as:
     - Start, accelerate, decelerate, stop, turn, or reverse.
     - Tow another vehicle (Truck-specific).
     - Perform a wheelie (Motorbike-specific).

4. **Exit**:
   - Exit the application when done.

## Dependencies

- [Inquirer](https://www.npmjs.com/package/inquirer): For interactive command-line prompts.
- [TypeScript](https://www.typescriptlang.org/): For type-safe development.

## Development

To make changes to the application:

1. Edit the TypeScript files in the `src` directory.
2. Rebuild the project:
   ```bash
   npm run build
   ```
3. Run the application to test changes:
   ```bash
   npm start
   ```

## Walkthrough Video

[Click here to watch the walkthrough video](https://drive.google.com/file/d/14WEkMqiNSgG71o2VqEMKwh8hEF2d64Hn/view?usp=sharing)

## License

This project is licensed under the ISC License.