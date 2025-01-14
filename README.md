# Daily Motivation Quote App

The **Daily Motivation Quote App** is designed to inspire users with motivational quotes. It fetches quotes from an online web service and displays them on the home screen. Users can easily navigate through quotes and share their favorite ones with friends.

## Key Features
- Fetch and display motivational quotes from a web service.
- Share quotes via social media or messaging apps.
- Enable daily notifications for a new quote every day.

## Wireframes
Below are the wireframes for the app:

1. **Home Screen**: Displays a motivational quote with buttons for "Next Quote" and "Share Quote."
2. **Settings Screen**: Allows users to enable/disable daily notifications and set their timing.

![splash screen](https://github.com/Priyanka0931/Dailymotiveapp/blob/main/splash%20screen.png?raw=true)

![Home Screen Wireframe](path/to/home_screen_wireframe.png)
![Settings Screen Wireframe](path/to/settings_wireframe.png)]

## Software Architecture
The app is designed using the Model-View-Controller (MVC) pattern:

- **MainActivity**: Handles UI and user interactions.
- **RetrofitClient**: Configures and manages API communication.
- **QuoteApi**: Defines API endpoints.
- **QuoteResponse**: Represents the JSON structure of the API response.

Below is the UML diagram illustrating these components:

![UML Diagram](path/to/uml_diagram.png)

## Technology Stack
- **Programming Language**: Kotlin (or Java)
- **Networking**: Retrofit for API calls
- **UI Design**: Android Material Design
- **API**: [They Said So Quotes API](https://theysaidso.com/)

## Web Service
This app fetches quotes from the [They Said So Quotes API](https://theysaidso.com/).
