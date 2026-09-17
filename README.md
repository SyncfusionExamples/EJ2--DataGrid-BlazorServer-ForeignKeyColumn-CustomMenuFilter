# Blazor Server DataGrid Foreign Key Column Custom Menu Filter

## Overview

This sample demonstrates how to customize filtering behavior for a foreign key column in a Syncfusion Blazor DataGrid by rendering a custom ComboBox component inside the Grid's menu filter interface. Rather than using the default filter UI, the sample provides a tailored filtering experience that allows users to select values from a predefined list associated with the foreign key data source. This approach is useful when foreign key values should be presented through a controlled selection experience instead of a standard filter input.

## Key Features

- Demonstrates a Syncfusion Blazor DataGrid foreign key column filtering scenario.
- Renders a custom ComboBox component inside the Grid menu filter UI.
- Uses a foreign key data source to present selectable filter values.
- Replaces the default menu filter experience with a customized component-based filter.
- Shows how Grid filtering can be integrated with a user-defined selection control.
- Includes supporting data models and sample data used by the foreign key column implementation.

## Prerequisites

* Visual Studio 2022

## How to Run the Project

1. Checkout this project to a location in your disk.
2. Open the `ForeignKeyWithCustomMenuFilter.sln` solution using Visual Studio 2022.
3. Restore the NuGet packages by rebuilding the solution.
4. Build the project successfully.
5. Run the application.
6. Navigate to the page containing the DataGrid sample.
7. Open the filter menu for the foreign key column and review the custom ComboBox-based filtering experience.

## Project Structure

- `Pages/` — contains the Razor page that renders the Syncfusion DataGrid and custom foreign key menu filter implementation.
- `Data/` — contains the sample data models and foreign key data source used by the Grid.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to DataGrid foreign key columns, see: https://help.syncfusion.com/grid-sdk/blazor/data-grid/foreignkey-column

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.