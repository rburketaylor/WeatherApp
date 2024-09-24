# Blazor Weather App

Welcome to the Blazor Weather App! This is a simple project designed to explore the capabilities of Blazor while providing a basic weather forecasting tool. The app fetches weather data from a public API and displays it in a user-friendly interface.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Real-time Weather Data**: Fetch current weather conditions based on user input.
- **User-friendly Interface**: Simple and intuitive UI built with Blazor components.
- **Responsive Design**: Works on various screen sizes.
- **Lightweight**: Minimal dependencies for quick loading.

## Technologies Used

- **Blazor**: For building interactive web UIs using C# instead of JavaScript.
- **ASP.NET Core**: Backend framework for hosting the application.
- **OpenWeatherMap API**: To fetch real-time weather data.
- **HTML/CSS**: For structuring and styling the application.

## Installation

To get started with the Blazor Weather App, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/rburketaylor/WeatherApp.git
   cd WeatherApp
   ```

2. **Install dependencies**:
   Make sure you have the [.NET SDK](https://dotnet.microsoft.com/download) installed. Then run:
   ```bash
   dotnet restore
   ```

3. **Add your OpenWeatherMap API key**:
   Sign up at [Tomorrow.io](https://app.tomorrow.io/signup) to get your API key. Create a new file named `secrets.json` in the connected services and add the following content:
   ```json
   {
     "API_KEYS": {
       "Service": "tomorrow.io",
       "Key": "YOUR_TOMORROW_IO_KEY"
     }
   }
   ```

4. **Run the application**:
   ```bash
   dotnet run
   ```
   You can open the provided localhost connection with CTRL+Click on the link.

## Usage

- Enter a city name in the search bar and hit "Get Weather."
- View the current temperature, humidity, and weather description.
- The app is designed for simplicity; you can modify and enhance it as you like!

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any feedback, suggestions, or improvements are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy exploring and expanding the Blazor Weather App!
