# ElevatorSimulation_JavaThreads

## About

ElevatorSimulation_JavaThreads is a project that simulates the operation of elevators controlled by a single controller to decrease the average waiting time for passengers. This project leverages Java threads to create a multi-threaded simulation of elevator systems.

## Project Structure

### Files

- **Controller.java**: The controller class that manages elevator requests and passenger pickups.
- **Elevator.java**: The elevator class that represents the individual elevators in the simulation.
- **ElevatorStatus.java**: An auxiliary enum class for elevator status (IDLE, GOING_UP, GOING_DOWN).
- **Main.java**: The main class that orchestrates the entire simulation. It creates passengers, elevators, and manages the simulation.
- **Passenger.java**: The passenger class that represents passengers in the simulation.

## How It Works

ElevatorSimulation_JavaThreads operates by simulating the behavior of elevators and passengers within a building. Here's a brief overview of how the project works:

1. Elevators are registered with the controller.
2. Passengers are generated and assigned random starting and destination floors.
3. Passengers request elevators to pick them up.
4. The controller manages elevator assignments and passenger pickups.
5. Elevators move to the requested floors to pick up and drop off passengers.
6. The simulation records waiting times and provides statistics on passenger arrivals and waiting times.

## Simulation Speed

The simulation runs approximately six times faster than real-time (12 seconds in simulation equals 2 seconds in real time) to expedite the simulation process.

## How to Use

To run the ElevatorSimulation_JavaThreads project:

1. Compile the Java files.
2. Run the `Main.java` class.
3. Observe the simulation as elevators pick up and drop off passengers.
4. View the simulation's output, including floor statistics and average waiting times.

## Acknowledgments

This project was created by John Isik as a simulation of elevator control using Java threads.

## License

This project is provided for educational purposes. Feel free to use and modify it as needed.
