# Gametime-Hero-RSVP-Service
This project is a TypeScript-based RSVP management module for events, built as part of the Gametime Hero Software Engineer Internship challenge. It supports adding, updating, and querying RSVP statuses of players.

## Features

- Add or update a player’s RSVP
- Get a list of confirmed attendees
- Count total, confirmed, and declined responses
- Accept user input interactively via terminal
- Fully type-safe using TypeScript interfaces
- Clean architecture with dependency injection and single responsibility principles

Getting Started:

1. Make sure you have node.js v18+ installed, then run:

   ```bash
   npm install

2. Download the zip file named gametime-hero-rsvp-service-assignment and then unzip it.

3. Open the unzipped gametime-hero-rsvp-service-assignment folder and then open your terminal/powershell in it.

4. In the terminal write the following command:

   ```bash
   npx ts-node gametime-hero-rsvp-service/index.ts

5. Alternate for step 4.
   If the above code is too complex, you can also simply write:
   
   ```bash
   npm run start

5. You'll be prompted in the terminal to enter:
   
   Player ID
   Player Name
   RSVP Status (Yes, No, or Maybe)

   You can add as many players as you'd like. Type done as the ID to finish input and see the output summary.

6. Run unit tests using:

   npm test

   Tests are written using Jest and ensure correctness of the RSVP logic.


This RSVP Manager project demonstrates clean, scalable TypeScript development with a focus on modular design, user interaction, and code quality. It follows modern engineering best practices such as dependency injection, interface-based architecture, and unit testing. Designed for seamless integration into a larger application like Gametime Hero, this project reflects my passion for writing maintainable, production-ready code and my enthusiasm for collaborative, user-focused software development.


   





