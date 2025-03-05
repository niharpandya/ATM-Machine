# ATM-Machine

This app uses ASP.NET Core and Angular.
The APIs use a local json file (database.json) to simulate the backend database/table.


## Valid PINs for Login

Enter the following PINs to ATM Demo App to simulate account logins. These credentials are stored in database.json.
 - 1111
 - 2222
 - 3333
 - 4444
 - 5555
 - 6666


## Run Locally

First, clone the project to your C: drive

Install Node.js

```bash
  Go to the official Node.js website.
  Download the LTS (Long Term Support) version for your operating system.
```

Install Angular CLI in global/root directory

```bash
  npm install -g @angular/cli
```

After Angular version after installation

```bash
  ng version
```

Navigate to '...ATM\ATM\atm.client' directory. Install npm packages:
```bash
  npm install
```

Open Visual Studio Solution
```bash
  Build solution by clicking Build -> Build Solution
  Click the "Start" button. It will automatically launch the web app in Microsoft Edge.
```

If Microsoft Edge doesn't open automatically, manually enter the following URL:
```bash
  https://localhost:60502/
```
