# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.64] - 2020-11-17
### Added
- BlazorServerApp project
  - EventCallback
  - EventCallback<T>
  - EventCallback<string>

## [0.1.61] - 2020-11-13
### Changed
- BlazorServerApp project using .NET 5.0
- BlazorSignalRApp.Server project using .NET 5.0

## [0.1.60] - 2020-11-12
### Added
- BlazorServerApp project
  - Radzen.Blazor nuget package (https://www.nuget.org/packages/Radzen.Blazor/)
  - Components.RadzenSample.Dialog
  - Components.RadzenSample.DialogCard
  - Components.RadzenSample.Notification
  - Components.RadzenSample.Tooltip
  - Components.RadzenSample.ContextMenu
  - Components.Attribute
  - Components.Content
  - Components.CounterAsync
### Changed
- BlazorServerApp project
  - Components.Forest
  - Components.Counter

## [0.1.30] - 2020-11-11
### Added
- BlazorServerApp project
### Removed
- BlazorApp project

## [0.1.20] - 2020-11-09
### Added
- BlazorSignalRApp.Client project
- BlazorSignalRApp.Server project
- BlazorSignalRApp.Shared project
### Changed
- BlazorApp project
- README.md

## [0.1.15] - 2020-11-05
### Added
- Assets png files
  - localhost_counter.png
  - localhost_dialog.png
  - localhost_fetchdata.png
  - localhost_home.png
  - localhost_todo.png
- .gitattributes
- .gitignore
- LICENSE.md
- README.md
- BlazorApp project
  - Pages\_Host.cshtml
  - Pages\Counter.razor
  - Pages\Dialog.razor
  - Pages\Error.cshtml
  - Pages\FetchData.razor
  - Pages\Index.razor
  - Pages\Todo.razor
  - Data\TodoItem.cs
  - Data\WeatherForecast.cs
  - Data\WeatherForecastService.cs
  - Shared\MainLayout.razor
  - Shared\NavMenu.razor
  - Shared\SurveyPrompt.razor
  - _Imports.razor
  - App.razor
  - appsettings.json
  - Program.cs
  - Startup.cs
