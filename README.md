# Espresso Home Assessment

Agent Managent App(Home Assessment)

## Features

### Core Features:

- **List of Agents**: Displays a list of agents with their details:
  - Name
  - Email
  - Status (Active/Inactive)
  - Last Seen Date
- **Add Agent**: A form to add a new agent.
  - Name (Text input)
  - Email (Validated email input)
  - Status (Active/Inactive dropdown)
- **Edit Agent**: Allows editing an agent's details.
- **Delete Agent**: An option to delete an agent with a confirmation popup.
- **State Management**: Uses React Context to manage state across the application.
- **Persistent Storage**: Agent data is saved in `localStorage` so it persists across page reloads.
- **Form Validation**: Basic validation for required fields (e.g., email validation).

### Optional Features (Implemented):

- **Responsive Design**: Make the UI responsive and mobile-friendly.
- **Unit Tests**: Basic unit tests for components using Jest and React Testing Library.

## Tech Stack

- **Framework**: Next.js which is a React framework for building server-side rendered applications.
- **Styling**: Tailwind CSS which utility-first CSS framework for styling the app.
- **State Management**: React Context for state management.
- **Storage**: localStorage for data persistence.
- **Language**: TypeScript which adds type safety and modern JavaScript features
- **Testing**: Jest & React Testing Library for unit testing React components.

## Instructions to Run the Application

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/tektheone/Agent-Management-App.git
   cd Agent-Management-App
   ```

2. **Install Dependencies**:
   Ensure you have Node.js installed. Then, run:

   ```bash
   npm install
   ```

3. **Run the Application**:
   To start the application locally, use the following command:

   ```bash
   npm run dev
   ```

4. **Access the Application**:
   Open your browser and go to [http://localhost:3000](http://localhost:3000). You will see the Agent Management App dashboard.

5. **Run Unit Tests**:
   To run the unit tests, use:
   ```bash
   npm run test
   ```

# Sample Images

![Agents List](https://github.com/tektheone/Agent-Management-App/blob/main/screenshots/1.%20Agents%20List.png)
![Add Agent](https://github.com/tektheone/Agent-Management-App/blob/main/screenshots/2.%20Add%20Agent.png)
![Added Agent](https://github.com/tektheone/Agent-Management-App/blob/main/screenshots/3.%20Added%20Agent.png?raw=true)
![Edit Agent](https://github.com/tektheone/Agent-Management-App/blob/main/screenshots/4.%20Edit%20Agent.png?raw=true)
