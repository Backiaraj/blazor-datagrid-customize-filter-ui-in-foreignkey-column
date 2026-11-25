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
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`CustomFilterUI.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-customize-filter-ui-in-foreignkey-column
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/filter-menu

**Online example**: https://blazor.syncfusion.com/demos/datagrid/filter-menu?theme=fluent2