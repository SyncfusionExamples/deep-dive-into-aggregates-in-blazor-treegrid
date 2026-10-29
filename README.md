# Deep Dive into Aggregates in Syncfusion Blazor TreeGrid

## Overview

This sample demonstrates how to configure and display aggregates in a Syncfusion [Blazor TreeGrid](https://www.syncfusion.com/blazor-components/blazor-tree-grid). The implementation covers built-in aggregate types (such as Sum and TrueCount), custom aggregates using custom logic, footer templates, and aggregate value formatting. These features provide summary information at the footer of columns, helping users analyze hierarchical data quickly and effectively in business and analytical applications.

## Key Features

- Demonstrates displaying summary values using aggregate columns in the Syncfusion Blazor TreeGrid component.
- Illustrates built-in aggregate functions such as `Sum` and `TrueCount`.
- Demonstrates custom aggregate calculation to display count of specific records based on custom logic.
- Shows how to customize aggregate appearance and content using `FooterTemplate`.
- Applies number formatting (`Format="n"`) to aggregate column values.
- Uses self-referencing hierarchical data binding with parent-child task relationships.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework (.NET 10.0 or later)

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `DeepDivetoAggregate.sln`

3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root.

```bash
cd deep-dive-into-aggregates-in-blazor-treegrid
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for this feature: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/aggregate

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
