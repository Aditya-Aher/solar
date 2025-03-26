# Solar Management System Setup

## Installation Steps

1. Create a new directory and navigate to it:
```bash
mkdir solar-management
cd solar-management
```

2. Create a new Angular project:
```bash
ng new solar-management --standalone --routing --style css
```
When prompted:
- Choose "Yes" for routing
- Choose "CSS" for styling

3. Replace the contents of the following files with the code from this project:

- `src/app/models/solar-panel.ts`
- `src/app/services/solar.service.ts`
- `src/app/dashboard/dashboard.component.ts`
- `src/app/add-recipient/add-recipient.component.ts`
- `src/main.ts`
- `src/global_styles.css`
- `src/index.html`

4. Update the dependencies in `package.json` to match:
```json
{
  "dependencies": {
    "@angular/animations": "^19.0.6",
    "@angular/common": "^19.0.6",
    "@angular/compiler": "^19.0.6",
    "@angular/core": "^19.0.6",
    "@angular/forms": "^19.0.6",
    "@angular/platform-browser": "^19.0.6",
    "@angular/router": "^19.0.6",
    "rxjs": "^7.8.1",
    "tslib": "^2.5.0",
    "zone.js": "~0.15.0"
  },
  "devDependencies": {
    "@angular/build": "^19.0.7",
    "@angular/cli": "^19.0.7",
    "@angular/compiler-cli": "^19.0.6",
    "typescript": "^5.6.3"
  }
}
```

5. Install dependencies:
```bash
npm install
```

6. Start the development server:
```bash
ng serve
```

The application will be available at `http://localhost:4200`

## Project Structure

```
src/
├── app/
│   ├── models/
│   │   └── solar-panel.ts
│   ├── services/
│   │   └── solar.service.ts
│   ├── dashboard/
│   │   └── dashboard.component.ts
│   └── add-recipient/
│       └── add-recipient.component.ts
├── main.ts
├── global_styles.css
└── index.html
```