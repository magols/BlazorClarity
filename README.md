# BlazorClarity


[![NuGet](https://img.shields.io/nuget/v/Magols.Blazor.Clarity.svg)](https://www.nuget.org/packages/Magols.Blazor.Clarity/)

Razor Class library with a component that renders Clarity snippet in HeadOutlet

## Usage
1. Add the package to your project
``` 
dotnet add package Magols.Blazor.Clarity
```
2. Include key in appsettings.json
```json
  "ClarityKey": "[YOUR_KEY]"
```
1. Add the following to your MainLayout.razor
```html
<BlazorClarity />
```