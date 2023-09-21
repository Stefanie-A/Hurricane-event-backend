# Hurricane Event Backend

This repository contains the backend code for the Hurricane Event project, which provides a RESTful API for managing events and related data on the events app.

## Installation

To run the Hurricane Event Backend locally, follow these steps:

1. **Clone the Repository and Activate the Virtual Environment:** 
   ```bash
   git clone https://github.com/your-username/hurricane-event-backend.git
   cd hurricane-event-backend
   virtualenv venv   # Create a virtual environment
   source venv/bin/activate  # Activate the virtual environment (Windows users: use venv\Scripts\activate)
   ```

2. **Install Required Dependencies:** 
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup Configuration:** 
   - Create a `config.py` file and configure the necessary environment variables, such as database connection details, API keys, and other configuration settings.

4. **Run the App:** 
   ```bash
   flask run
   ```

The list you provided is a good start, but it could be more informative and complete. Here's an expanded and more detailed version:

## Usage

The Hurricane Event Backend provides a comprehensive set of API endpoints to facilitate the management of events and related data in the events app. Below are some key API endpoints and their corresponding functionalities:

### Event Management

- **Retrieve Events:**
  - `GET /api/events`: Fetch a list of events with optional filters (e.g., date, location, category).
  - `GET /api/events/{event_id}`: Retrieve detailed information about a specific event by its unique identifier.

- **Create, Update, and Delete Events:**
  - `POST /api/events`: Create a new event by providing event details.
  - `PUT /api/events/{event_id}`: Update an existing event's information.
  - `DELETE /api/events/{event_id}`: Remove an event from the system.

### User Account Management

- **User Registration and Authentication:**
  - `POST /api/users/register`: Register a new user account by providing necessary details (e.g., username, email, password).
  - `POST /api/users/login`: Authenticate a user and obtain an access token for subsequent API requests.
  - `POST /api/users/logout`: Log out and invalidate the access token.

- **User Profile Management:**
  - `GET /api/users/{user_id}`: Retrieve user profile information.
  - `PUT /api/users/{user_id}`: Update user profile information (e.g., name, email, password).

### Event Location Management

- **Retrieve and Manage Locations:**
  - `GET /api/locations`: Fetch a list of event locations.
  - `GET /api/locations/{location_id}`: Retrieve detailed information about a specific location.
  - `POST /api/locations`: Create a new event location.
  - `PUT /api/locations/{location_id}`: Update information about an existing location.
  - `DELETE /api/locations/{location_id}`: Remove a location from the system.

### Event Category Management

- **Retrieve and Manage Categories:**
  - `GET /api/categories`: Fetch a list of event categories.
  - `GET /api/categories/{category_id}`: Retrieve detailed information about a specific category.
  - `POST /api/categories`: Create a new event category.
  - `PUT /api/categories/{category_id}`: Update information about an existing category.
  - `DELETE /api/categories/{category_id}`: Remove a category from the system.

This is a more comprehensive overview of the key API endpoints and their respective functionalities within the Hurricane Event Backend. It should help users and developers better understand how to interact with the API. Remember to include any additional endpoints or functionalities specific to your application.

For detailed documentation on these API endpoints and their usage, please refer to the [DOCUMENTATION.md](DOCUMENTATION.md) file.

## Contributing

Contributions to the Hurricane Event Backend are welcome! If you encounter any issues, have suggestions for improvements, or want to contribute to the project, please follow these guidelines:

1. **Check for Existing Issues:** Before creating a new issue or submitting a pull request, check if a similar issue or pull request already exists.

2. **Create a New Branch:** When working on a contribution, create a new branch from the `main` branch.

3. **Submit a Pull Request:** After making your changes, submit a pull request, providing a clear description of the changes you've made and why they are beneficial.

Before contributing, please review the detailed [Contribution Guidelines](CONTRIBUTING.md) for more information.

## Contact

For any inquiries or questions related to the Hurricane Event Backend, please feel free to contact the project and backend team leads:

### Project Team Lead

- **Name:** [Your Project Team Lead Name]
- **Email:** team.lead@example.com
- **GitHub:** [@Project_team_lead](https://github.com/Project_team_lead)

### Backend Team Lead

- **Name:** [Your Backend Team Lead Name]
- **Email:** team.lead@example.com
- **GitHub:** [@Project_backend_team_lead](https://github.com/Project_backend_team_lead)

Your README is now organized, informative, and user-friendly, making it easier for contributors and users to understand and use your Hurricane Event Backend.
