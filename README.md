# QuoteAppPart1

## Overview
QuoteAppPart1 is a simple application for storing and retrieving inspirational quotes, utilizing serialization and deserialization for persistent data storage.

## Features
- **Persistent Storage**: Saves quotes locally.
- **Quote Management**: Add, retrieve, and manage stored quotes.

## Architecture
- **MVVM (Model-View-ViewModel)**: Separates concerns for maintainability.
- **JSON-Based Storage**: Lightweight and structured data persistence.
- **Event-Driven UI Updates**: Uses `INotifyPropertyChanged` for automatic refresh when data changes.

## Tech Stack

### Tools  
- **Visual Studio Code (1.99.0)** – Documentation and README refinement.  
- **Microsoft Visual Studio Community 2022 (17.13.5)** – Development and debugging.  
- **Git (2.45.1.windows.1)** – Version control.  
- **GitHub** – Remote repository management.

## Installation

### Pre-requisites
1. Install the following:
   - [.NET SDK](https://dotnet.microsoft.com/download/dotnet) (6.0 or later).
   - Visual Studio 2022 Community Edition (with .NET MAUI workload).
   - Git (2.45 or later).

2. Clone the repository:
   ```bash
   git clone https://github.com/Learner062022/QuoteAppPart1.git
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
    Restore NuGet packages:  
    ```bash
    dotnet restore
    ```

  - **Build Errors**  
    Verify project references and bindings in `.csproj`.  

- **Simulator Issues**  
  - Restart the development environment if the emulator fails to load.  
  - Enable developer mode on physical devices.  

## Troubleshooting
- Employed manual debugging techniques:
  - Used breakpoints to inspect execution flow.
  - Monitored variable states and logic with `Debug.WriteLine`.
  - Analyzed the stack for issue resolution.

## Testing and Validation

### Manual Testing Approach
- **Exploratory Testing**: Navigated through the app to verify core functionality.
- **Debugging Techniques**: Applied breakpoints and `Debug.WriteLine` for validation.
- **Edge Cases Checked**:
  - Managed empty or invalid quote entries.
  - Ensured proper quote formatting.
  - Verified JSON persistence after application restart.
  - Tested recovery from missing file (e.g., deleted text file).

## Contributing

### Guidelines
- Adhere to [Google's Style Guides](https://google.github.io/styleguide/) or [Microsoft's C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) for clean and maintainable code.
- Provide detailed descriptions of changes and link related issues in all pull requests.

### Branching Strategy
- Follow [Conventional Commits](https://www.conventionalcommits.org/) for commit message formatting. 
- Refer to [Microsoft's Branching Guidance](https://learn.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance?view=azure-devops) or [GitKraken's Git Branching Strategies](https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy).

### Pull Requests
- Submit all pull requests to the `main` branch following [GitHub's Pull Request Guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-pull-requests).
- Ensure new features or updates are well-documented. Refer to [Atlassian's Pull Request Guide](https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests) for best practices.

## License
The project is licensed under the [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html).