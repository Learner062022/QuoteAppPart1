# QuoteAppPart1

## Project Overview

## Motivation

## Goal

## Features

## Architecture

## Tech Stack

### Frameworks and Libraries  

### Tools  
- **Visual Studio Code (1.99.0)**: For writing and refining the README file.  
- **Microsoft Visual Studio Community 2022 (17.13.5)**: IDE used for creating and debugging the application.  
- **Git (2.45.1.windows.1)**: Version control system for managing code changes and tracking project history.  
- **GitHub**: Remote repository platform for storing the project and enabling centralized access.

## Installation and Usage

### Pre-requisites
1. Ensure the following are installed on your system:  
   - [.NET SDK](https://dotnet.microsoft.com/download/dotnet) (version 6.0 or later).  
   - Visual Studio 2022 Community Edition or higher with the .NET MAUI workload installed.  
   - Git (version 2.45 or later) for version control.

2. Clone the repository from GitHub:  
   ```bash
   git clone https://github.com/Learner062022/TipCalculatorPart2.git
   ```

### Step-by-step Instructions
- **Open the Project**  
  - Launch Visual Studio 2022 Community Edition.  
  - Open the cloned project by navigating to the folder containing the `.csproj` file.  

- **Build the Solution**  
  - In Visual Studio, navigate to *Build* > *Build Solution* (or use the shortcut `Ctrl + Shift + B`).  

- **Run the Application**  
  - Click the *Start* button or press `F5` to debug and run the application.  
  - The app will launch in the specified simulator/emulator or on your connected physical device.  

### Troubleshooting
- **Common Errors**  
  - **Missing Dependencies**  
    Ensure all required NuGet packages are restored by running:  
    ```bash
    dotnet restore
    ```

  - **Build Errors**  
    Confirm that all project references and bindings are correct in the `.csproj` file.  

- **Simulator Issues**  
  - Restart your development environment if the emulator/simulator fails to load.  
  - For physical devices, ensure developer mode is enabled.  

## Troubleshooting
- Used manual debugging techniques, including setting breakpoints to inspect code execution flow, employing 'Debug.WriteLines' statements to monitor variable states and logic and analyzing the stack to trace and resolve the issues effectively. 

## Testing and Validation
- Conducted functional testing by running the application to verify its core features, such as saving preferences, navigation and customization options, operated as expected. No automated or formalized testing methods were used beyond running the application to confirm basic functionality.

### Edge Cases

## Limitations

## Future Improvements

## Contributing

### Guidelines
- Adhere to [Google's Style Guides](https://google.github.io/styleguide/) or [Microsoft's C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) for clean and maintainable code.
- Provide detailed descriptions of changes and link related issues in all pull requests.

### Branching Strategy
- Follow [Conventional Commits](https://www.conventionalcommits.org/) for commit message formatting. Use branch naming conventions such as:
  - `feature/<description>`: For new features.
  - `fix/<description>`: For bug fixes.
  - `hotfix/<description>`: For critical fixes.
- Refer to [Microsoft's Branching Guidance](https://learn.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance?view=azure-devops) or [GitKraken's Git Branching Strategies](https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy) for workflows:
  - Branch off from the latest `main`.
  - Regularly sync branches with `main` and ensure thorough testing prior to pull requests.

### Pull Requests
- Submit all pull requests to the `main` branch following [GitHub's Pull Request Guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-pull-requests).
- Ensure new features or updates are well-documented. Refer to [Atlassian's Pull Request Guide](https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests) for best practices.

## Known Issues

## License
The project is licensed under the [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html).