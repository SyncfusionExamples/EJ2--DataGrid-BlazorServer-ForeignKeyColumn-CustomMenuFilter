# Blazor DataGrid with Foreign Key Column and Custom Menu Filter

A sample Blazor Server application demonstrating how to use a custom dropdown component in the menu filter of a Foreign Key column in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This project showcases best practices for rendering custom filter templates in Foreign Key columns. It demonstrates how to integrate a `SfDropDownList` component as a custom filter interface within the DataGrid's menu filter, providing a seamless user experience for filtering related data.

## Key Features

- **Foreign Key Column Support**: Link related data from employee records to orders
- **Custom Filter Templates**: Render dropdown components directly in the filter menu
- **Interactive DataGrid**: Sort, page, and filter order data with employee information
- **Responsive Design**: Bootstrap-based responsive layout

## Prerequisites

- [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/EJ2--DataGrid-BlazorServer-ForeignKeyColumn-CustomMenuFilter.git
cd ForeignKeyWithCustomMenuFilter
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```


## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/foreignkey-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/foreign-key-column?theme=bootstrap5