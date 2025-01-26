Team Name: SANKALPAM
Team Members

    Member 1: ANITA SUSAN THOMAS - SAINTGITS COLLEGE OF ENGINEERING
    Member 2: MALAVIKA HARIDAS - SAINTGITS COLLEGE OF ENGINEERING
   

Hosted Project Link : https://anitathomas31.github.io/buslist/

Project Description:A website that allows users to select a location and view a list of buses, including their departure times from the main bus stand and arrival times at the 
final destination bus stand.It also shows ticket rate.It also allows users to file complaints regarding the problems they face.

The Problem statement:Hard to find the exact departure and arrival  timing of the private bus. No specific platform to file complaint against the private bus.

The Solution: Made a website that allows users to select a location and view a list of buses, including their departure times from the main bus stand and arrival times at the 
final destination bus stand.It also shows ticket rate.It also allows users to file complaints regarding the problems they face.

Technical Details
Technologies/Components Used

For Software:

    html,css
    CodePen
Implementation
  For Software:Visual Studio Code

SCREENSHOTS:-


DIAGRAMS:-
                            +---------------------------+
                            |      Frontend (HTML)      |
                            +---------------------------+
                                      |
                                      |
                    +------------------------------------------+
                    |              Web Page UI                |
                    |------------------------------------------|
                    |   - Dropdown for Origin and Destination  |
                    |   - List of Buses Available             |
                    |   - Complaint Form                      |
                    +------------------------------------------+
                                      |
                                      |
               +-------------------------------------------+
               |              JavaScript Logic            |
               |-------------------------------------------|
               | 1. Event Handlers                         |
               |   - Origin & Destination Selection (Change Event)|
               |   - Complaint Form Submission (Submit Event)|
               +-------------------------------------------+
                                      |
                                      |
               +-------------------------------------------+
               |                Data Structures          |
               |-------------------------------------------|
               | 1. Bus Routes Data (busRoutes Object)     |
               | 2. Ticket Prices Data (busPrices Object)  |
               +-------------------------------------------+
                                      |
                                      |
              +--------------------------------------------+
              |           Update Bus List Logic           |
              |--------------------------------------------|
              |   - Retrieves origin and destination from |
              |     dropdown values                        |
              |   - Matches routes and displays available |
              |     buses with departure/arrival times    |
              |   - Shows ticket price for selected route |
              |   - Handles cases where no routes are found|
              +--------------------------------------------+
                                      |
                                      |
             +----------------------------------------------+
             |               Complaint Submission           |
             |----------------------------------------------|
             |   - Receives and displays submitted complaint|
             |   - Displays thank-you response after form   |
             |     submission                               |
             +----------------------------------------------+

