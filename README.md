# Incident Management Application

## Description
A simple incident management application built with Node.js for the backend and plain HTML/CSS/JavaScript for the frontend.

## Features
- Add incidents with a title and description.
- View a list of incidents.
- Update the status of an incident (e.g., mark as resolved).
- Delete incidents.

## Prerequisites
- Node.js installed.
- Basic understanding of JavaScript and web development.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd incident-management
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the server:
   ```bash
   npm run start
   ```
2. Open the `index.html` file in your browser.
3. Interact with the application to add, update, or delete incidents.

## Project Structure
```
incident-management/
├── index.js          # Backend server
├── package.json      # Node.js dependencies
├── package-lock.json # Dependency lock file
├── public/           # Frontend files
│   ├── index.html    # Frontend HTML file
│   ├── style.css     # Frontend styles (optional)
│   └── script.js     # Frontend JavaScript
```

## API Endpoints
1. `GET /api/incidents`
   - Retrieve all incidents.
2. `POST /api/incidents`
   - Create a new incident.
   - Body: `{ title: string, description: string, status?: string }`
3. `PUT /api/incidents/:id`
   - Update an incident's status.
   - Body: `{ status: string }`
4. `DELETE /api/incidents/:id`
   - Delete an incident by ID.

## License
This project is open-source and available under the MIT License.
