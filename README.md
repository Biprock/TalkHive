# TalkPulse

A real-time chat application built using Django Channels and WebSocket protocol. This application leverages ASGI instead of WSGI to handle WebSocket connections, enabling real-time communication between clients.

## Features

- Real-time messaging with WebSocket protocol
- User authentication for secure access
- Django Channels integration for handling WebSocket connections
- Clean and responsive UI for an enhanced user experience

## Tech Stack

- **Backend:** Django, Django Channels
- **Frontend:** HTML, CSS, JavaScript
- **WebSocket:** ASGI, Django Channels
- **Database:** SQLite (default, can be configured to use other databases)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/TalkHive.git
    cd TalkHive
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Run the database migrations:**
    ```bash
    python manage.py migrate
    ```

4. **Create a superuser (optional, for admin access):**
    ```bash
    python manage.py createsuperuser
    ```

5. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

6. **Access the application:**
    Open your browser and go to `http://127.0.0.1:8000/`

## Usage

1. Register a new account or log in with existing credentials.
2. Start a new chat room or join an existing one.
3. Send and receive messages in real-time.

## Screenshots

![WhatsApp Image 2024-06-29 at 11 44 21](https://github.com/Biprock/TalkHive/assets/85643598/f63c98a4-f20b-49c3-8091-1e07ee1b10e3)



https://github.com/Biprock/TalkHive/assets/85643598/7bb14c92-d708-42a8-ac2c-a3e1afcf1fe2



## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.



