# StudentInfoApp

**Mastering Blazor with Visual Studio 2026**

A comprehensive student information management application built with Blazor, demonstrating modern web development practices and component-based architecture.

## Overview

StudentInfoApp is an educational project showcasing best practices for building interactive web applications using Blazor and Visual Studio 2026. This application provides a platform for managing and displaying student information with a responsive, user-friendly interface.

## Tech Stack

| Technology | Percentage | Purpose |
|-----------|-----------|---------|
| **CSS** | 47.4% | Styling and responsive design |
| **HTML** | 40.1% | Markup and page structure |
| **JavaScript** | 9.5% | Client-side interactivity and DOM manipulation |
| **C#** | 3% | Backend logic and Blazor components |

## Features

- **Student Information Management** - Create, read, update, and delete student records
- **Responsive Design** - Mobile-friendly interface that works across all devices
- **Interactive Components** - Blazor components for dynamic user interactions
- **Modern UI** - Clean and intuitive user interface with professional styling

## Getting Started

### Prerequisites

- Visual Studio 2026 or later
- .NET 8.0 or later
- A modern web browser (Chrome, Firefox, Safari, or Edge)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/liewvk/StudentInfoApp.git
cd StudentInfoApp
```

2. Open the solution in Visual Studio 2026

3. Restore NuGet packages:
```bash
dotnet restore
```

4. Build the project:
```bash
dotnet build
```

### Running the Application

1. Set the startup project to the main application
2. Press `F5` or click the Run button in Visual Studio
3. The application will open in your default browser at `https://localhost:7000` (or similar)

## Project Structure

```
StudentInfoApp/
├── Components/          # Blazor components
├── Pages/              # Page components and routing
├── Services/           # Business logic and data services
├── wwwroot/            # Static files (CSS, JavaScript, images)
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   └── images/         # Image assets
├── Models/             # Data models
└── appsettings.json    # Configuration file
```

## Key Components

- **StudentList** - Display and manage all students
- **StudentDetail** - View detailed student information
- **StudentForm** - Form for adding/editing student records
- **Navigation** - Application navigation menu

## Development Notes

This project demonstrates several Blazor concepts:

- **Component Composition** - Reusable Blazor components
- **Data Binding** - Two-way binding in Blazor
- **Event Handling** - Handling user interactions
- **Routing** - Page navigation and URL routing
- **State Management** - Managing application state
- **CSS Isolation** - Component-scoped styling

## Styling Approach

The application uses a combination of:
- **Custom CSS** - Tailored styles for specific components
- **Responsive Design** - Mobile-first approach with media queries
- **CSS Flexbox & Grid** - Modern layout techniques

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## Learning Resources

For more information about Blazor and Visual Studio 2026, check out:
- [Official Blazor Documentation](https://learn.microsoft.com/en-us/aspnet/core/blazor/)
- [C# Language Documentation](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [Visual Studio Documentation](https://learn.microsoft.com/en-us/visualstudio/)

## License

This project is provided as an educational resource. Please refer to the LICENSE file for more information.

## Contact & Support

For questions or support regarding this project, please open an issue on the GitHub repository.

---

**Last Updated:** 2026-09-11

**Status:** Active Development ✅
