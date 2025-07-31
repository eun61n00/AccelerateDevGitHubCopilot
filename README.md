Coming soon

# Library App

## Description

Library App is a modular .NET solution for managing a library system. It provides core domain logic, infrastructure for data access, a console-based user interface, and unit tests for reliability. The application supports patron management, book loans, and membership renewals.

## Project Structure

-   AccelerateDevGitHubCopilot.sln
-   README.md
-   src/
    -   Library.ApplicationCore/
        -   Library.ApplicationCore.csproj
        -   Entities/
        -   Enums/
        -   Interfaces/
        -   Services/
    -   Library.Console/
        -   appSettings.json
        -   CommonActions.cs
        -   ConsoleApp.cs
        -   ConsoleState.cs
        -   Library.Console.csproj
        -   Json/
        -   Program.cs
    -   Library.Infrastructure/
        -   Library.Infrastructure.csproj
        -   Data/
-   tests/
    -   UnitTests/
        -   LoanFactory.cs
        -   ...

## Key Classes and Interfaces

-   [`Library.Console.ConsoleApp`](src/Library.Console/ConsoleApp.cs): Main logic for the console application, manages user interaction and state.
-   [`Library.Console.ConsoleState`](src/Library.Console/ConsoleState.cs): Tracks the current state of the console UI.
-   `Entities/`: Domain models for patrons, books, loans, etc.
-   `Interfaces/`: Abstractions for repositories and services.
-   `Services/`: Business logic implementations.
-   `Data/`: Infrastructure for data storage and retrieval.
-   `UnitTests/`: Contains unit tests for core logic and features.

## Usage

1. **Build the project:**
    ```sh
    dotnet build AccelerateDevGitHubCopilot.sln
    ```
