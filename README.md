# Pomodoro

A Pomodoro timer web application built with Blazor Server on ASP.NET Core.

## Features

* Pomodoro technique: 25 minutes work, 5 minutes break.
* Real-time UI updates using SignalR.
* Circular timer display and session counter.
* Audio notification at session end.

## Technology Stack

* [.NET 8.0](https://dotnet.microsoft.com/)
* C# 12
* ASP.NET Core & Blazor Server
* Razor Components (.razor)
* HTML5 & CSS3 (using CSS variables)
* SignalR for real-time communication
* Audio playback via HTML5 `<audio>` tag

## Prerequisites

* .NET 8.0 SDK installed
* IDE: Visual Studio 2022+ or VS Code with C# extension

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/hemanthhoney/Pomodoro.git
   cd Pomodoro
   ```

2. Restore dependencies and run the app:

   ```bash
   dotnet restore
   dotnet run
   ```

3. Open your browser and navigate to `https://localhost:5001`.

## Project Structure

```
Pomodoro/
├── Program.cs
├── PomodoroBlazor_UI.csproj
├── Pages/
│   ├── _Host.cshtml
│   ├── Pomodoro.razor
├── Shared/
│   ├── MainLayout.razor
│   ├── NavMenu.razor
│   ├── TabNav.razor
│   ├── CircularTimer.razor
│   ├── TimerDisplay.razor
│   └── SessionCounter.razor
└── wwwroot/
    ├── css/
    │   ├── variables.css
    │   └── app.css
    └── sounds/
        └── ding.mp3
```

## Usage

* Click **Start** to begin a Pomodoro session.
* Watch the timer count down in the circular display.
* After 25 minutes, hear the "ding" sound and take a 5-minute break.
* Repeat cycles for productivity.

## Contributing

Contributions are welcome! Please open issues or submit pull requests.

## Contact

Created by Hemanth
Contact: hemanthhoney.s@gmail.com
