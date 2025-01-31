# Health Challenge Tracker

## Overview

Health Challenge Tracker is an Angular 14+ single-page application (SPA) designed to help users track their workouts. This application allows users to input their name, workout type, and duration, and displays the workout data in a searchable, filterable table with pagination.

## Features

- Add new workouts with user name, workout type, and duration
- Display workouts in a table grid
- Search functionality by username
- Filter workouts by workout type
- Pagination (5 users per page)
- Data persistence using localStorage
- Responsive design with Tailwind CSS
- Unit tests for components and services with 100% code coverage

### Optional Feature
- Workout progress visualization using charts

## Tech Stack

- Angular 14+
- Tailwind CSS
- Angular Material (for UI components)
- Chart.js (for optional charting feature)

## Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later)


## Installation

1. Clone the repository:  
   ```sh
   git clone https://github.com/Tejaspatil06/Health-Tracker.git
   ```

2. Navigate to the project directory:  
   ```sh
   cd Health-Tracker
   ```

3. Install dependencies:  
   ```sh
   npm install
   ```

4. Start the development server:  
   ```sh
   ng serve
   ```

5. Open your browser and visit [`http://localhost:4200`](http://localhost:4200)

## Running Tests

To run the unit tests and generate a coverage report, run:  
```sh
ng test --code-coverage
```
The coverage report will be available in the `coverage` folder.

## Build

To build the project, run:  
```sh
ng build
```
The build artifacts will be stored in the `dist/` directory.

## Testing 

- Console Image
![Console Log Image](https://github.com/Tejaspatil06/Health-Tracker/blob/main/public/log.png)

- Coverage Testing
![Console Log Image](https://github.com/Tejaspatil06/Health-Tracker/blob/main/public/coverage.png)
  
## Deployment

This application is deployed on [Vercel](https://vercel.com/tejaspatil06s-projects).  
You can access the live version at [Health Tracker](https://health-tracker-five-tau.vercel.app).


## Assumptions

- Workout types are predefined (e.g., Running, Cycling, Swimming, Yoga).
- User data is stored locally and not shared between different browsers/devices.
- The application is intended for personal use and does not require user authentication.

## Future Enhancements

- User authentication and profiles
- Backend integration for data persistence
- More detailed workout tracking (e.g., calories burned, distance)
- Social features (e.g., sharing workouts, challenges)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
