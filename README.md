# Scheduling-Application

Scheduling app is a web based application used in conjunction with the I-9 Anywhere API to select and schedule appointment times and locations. Users can provide an address and the application will display all the available locations within the search criteria. The user can then select their desired location and the application will display the available times. Users can choose their preferred time and the application will block out a spot in the calendar for the appointment.

## Technologies Used

* Angular 2+
* Angular Material
* HTML
* CSS
* Karma
* Jasmine
* TypeScript 

## Features

* Request available locations and times relative to a user submited address.
* Create/cancel an appointment at appropriate locations.
* View created appointments on the user calendar.

## Getting Started

Follow these steps to set up the project.

1. Make sure you have git installed.
2. Clone this repository in a folder.
3. The Google Maps API and I-9 Anywhere API need valid keys in the environment.ts file. Change these to the your credentials.
4. In order to run the angular project, you need to have node.js installed. Then use "npm install" in the angular project folder to get the necessary dependencies.
5. Use "ng serve" to run the angular project. It will default to running on port 4200.
