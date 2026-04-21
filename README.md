# ASP.NET CORE DataGrid - Editing FrozenColumns Focus Clicked Cell

## Repository Description

This repository contains an ASP.NET Core sample that demonstrates how to focus the clicked cell during normal editing when frozen columns are enabled in a Syncfusion ASP.NET Core DataGrid.

## Project Overview

This sample explains how to maintain focus on the selected cell while performing edit operations in an ASP.NET Core DataGrid that uses frozen columns. When frozen columns are present, the focus behavior during editing can differ from standard grids, and in some scenarios the active cell focus may shift unexpectedly. To address this, the sample leverages JavaScript’s `focus` method inside the DataGrid `actionComplete` event to ensure that the clicked cell remains focused even when it belongs to a frozen column section.

The project serves as a targeted reference for handling focus and editing behavior in grids that combine frozen columns with normal edit functionality, using ASP.NET Core DataGrid features and client-side scripting.

## Key Features

- Editing support with frozen columns in ASP.NET Core DataGrid
- Retains focus on the clicked cell during edit actions
- Demonstrates JavaScript integration with DataGrid events

## Prerequisites

- Visual Studio 2022
- ASP.NET Core compatible .NET SDK

## Running the Application

Follow the steps below to clone the repository, restore dependencies, and run the application.

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone <repository-url>
   cd ASPNET-Core-DataGrid-Editing-FrozenColumns-Focus-Clicked-Cell
   ```

2. Restore the required NuGet packages:

   ```bash
   dotnet restore
   ```

3. Run the application using the .NET CLI or Visual Studio:

   ```bash
   dotnet run
   ```

Launch the displayed application URL in a browser, enable editing on the grid, and click a cell in either frozen or movable columns to observe that the clicked cell retains focus during editing.

## Additional Resources

- [Move the focus to a particular cell instead of first cell while editing a row](https://ej2.syncfusion.com/aspnetcore/documentation/grid/editing/in-line-editing#move-the-focus-to-a-particular-cell-instead-of-first-cell-while-editing-a-row)
- [Syncfusion ASP.NET Core Grid Editing](https://ej2.syncfusion.com/aspnetcore/documentation/grid/editing/)
- [Syncfusion ASP.NET Core Grid Documentation](https://ej2.syncfusion.com/aspnetcore/documentation/grid)
- [Syncfusion ASP.NET Core Demos](https://ej2.syncfusion.com/aspnetcore)
