# Blazor DataGrid — Custom Filter UI in Foreign Key Column

A sample Blazor application demonstrating how to implement custom filter UI components for foreign key columns in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This repository shows how to create and integrate custom filter components for foreign key columns in a Blazor DataGrid. Instead of using the default filter UI, you can provide a tailored filtering experience with dropdowns and other interactive components for related data lookups.

The example demonstrates binding a DataGrid to employee and order data, then customizing the filter UI for the employee foreign key column to display employee names using a dropdown list.

## Features

- **Custom Filter Templates** - Create tailored filter UI for foreign key columns using Razor components
- **Interactive Dropdown Filters** - Implement dropdown list filters for seamless data selection
- **Related Data Binding** - Bind nested objects using `ForeignKeyValue` to display meaningful data
- **Menu-Based Filtering** - Built-in menu filter type for intuitive column filtering
- **Real-time Filtering** - Apply filters instantly with Syncfusion dropdown components
- **Reusable Patterns** - Extend to other columns and customize with different components

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-customize-filter-ui-in-foreignkey-column.git
cd blazor-datagrid-customize-filter-ui-in-foreignkey-column
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

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/filter-menu

**Online example**: https://blazor.syncfusion.com/demos/datagrid/filter-menu?theme=fluent2