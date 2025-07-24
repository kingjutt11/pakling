# Architecture Workflow Manager

## Overview
The Architecture Workflow Manager is a comprehensive software solution designed to streamline the workflow of architecture firms. This application facilitates efficient management of client and vendor data, quotation generation, invoice management, purchase orders, complaints, stock reports, expense tracking, and various financial reports.

## Features
- **Client Management**: Input and retrieve client data with ease.
- **Vendor Management**: Manage vendor information and relationships.
- **Quotation Generation**: Create and manage quotations for projects.
- **Invoice Management**: Generate and track invoices for services rendered.
- **Purchase Orders**: Handle purchase orders efficiently.
- **Complaint Management**: Record and manage client complaints.
- **Stock Reports**: Generate stock reports based on invoices.
- **Expense Tracking**: Track and manage expenses related to projects.
- **Financial Reports**: Generate various financial reports for analysis.

## Technology Stack
- **Programming Language**: C#
- **Database**: SQL Server (or any compatible database)
- **Framework**: .NET Core
- **Server**: ASP.NET Core Web API

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/architecture-workflow-manager.git
   ```
2. Navigate to the project directory:
   ```
   cd architecture-workflow-manager
   ```
3. Restore the dependencies:
   ```
   dotnet restore
   ```
4. Update the `server/config/serverConfig.json` file with your database connection string and server settings.
5. Run the application:
   ```
   dotnet run --project src/main.cs
   ```

## Usage
- Access the application through the configured server URL.
- Use the API endpoints to manage clients, vendors, quotations, invoices, and more.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Thanks to the open-source community for their contributions and support.