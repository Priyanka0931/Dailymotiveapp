# Daily Motivation Quote App

The **Daily Motivation Quote App** is designed to inspire users with motivational quotes. It fetches quotes from an online web service and displays them on the home screen. Users can easily navigate through quotes and share their favorite ones with friends.

## Key Features
- Fetch and display motivational quotes from a web service.
- Share quotes via social media or messaging apps.
- Enable daily notifications for a new quote every day.

## Wireframes
Below are the wireframes for the app:

1. **Splash Screen**: Displays the logo of the app
2. **Home Page**: allows user to sign or sign up to the app
3. **Sign in**: Allows user to login to the app
4. **Sign up**: Allows user to create a account for the app
5. **Quote Page**: Displays a motivational quote with buttons for "Next Quote" and "Share Quote."
6. **Menu**: Allows users to enable/disable daily notifications and view saved quotes.

                                             
![Splash Screen](https://github.com/Priyanka0931/Dailymotiveapp/blob/main/splash%20screen.png?raw=true).   ![Home](https://github.com/Priyanka0931/Dailymotiveapp/blob/main/home.png?raw=true)

![Sign in](https://github.com/Priyanka0931/Dailymotiveapp/blob/main/sign%20in.png?raw=true)     ![Sign up](https://github.com/Priyanka0931/Dailymotiveapp/blob/main/sign%20up.png?raw=true)


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
