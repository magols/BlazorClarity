# BlazorClarity
Razor Class library with a component that renders Clarity snippet in HeadOutlet

## Usage
1. Add the package to your project
2. Include key in appsettings.json
```json
  "ClarityKey": "[YOUR_KEY]"
```
3. Add the following to your MainLayout.razor
```html
<BlazorClarity />
```