# SchematicsTest

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.6.

## Project introduction

1. Video ref Pluralsight: Building Reusable Angular Components

### Task: Add Angular Material

1. Run `ng add @angular/material`
2. Run `npm install`

### Task: Add a material dashboard (using schematic)

1. run `ng generate @angular/material:material-dashboard --name my-dash`
2. ERROR: `Schematic "@angular/material-dashboard" not found in collection...`
3. Ref: <https://stackoverflow.com/questions/51335789/schematic-materialdashboard-not-found-in-collection-angular-material>

```html
materialShell => material-shell
materialDashboard => material-dashboard
materialNav => material-nav
materialTable => material-table
```

### Task: Display the dash component

Use #1: Compose multiple components together in the required configuration and work correctly

### Task: Add a material table (using schematic)

1. run `ng generate @angular/material:material-table --name my-table`

Use #2: Scafold out a complex component and wire up supporting code
