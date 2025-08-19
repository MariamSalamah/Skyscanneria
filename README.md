# Skyscanneria
This project is a flight &amp; hotel booking application inspired by Skyscanner website.

## Content
    - [Flowchart](#flowchart)
    - [Sequence Diagram](#sequence-diagram)
    - [Pseudocode](#pseudocode)
 
## Flowchart 
#### Search Flights by a Guest Flow
<img src="https://github.com/MariamSalamah/Skyscanneria/blob/main/search%20flights.png" alt="Search Flights Flowchart" width="80%" />
<!-- #### Filter Flights (for a guest) Flow
<img src="https://github.com/MariamSalamah/Vacation-Tracking-System/blob/main/Create%20Request%20flowchart.svg" alt="Creat Request Flowchart" width="80%" /> -->


## Sequence diagram
![Search Flights As a Guest Sequance Diagram]()

## Pseudocode

**Search Flights As a Guest**
```plaintext
FUNCTION SearchFlight(flightDetails):

Step 1: newFlightRequest(flightDetails)
        Request DetailsPage (DP) with flightDetails
        DP returns availableFlights to Main Page (main)

Step 2: checkFlightAvailability(flightDetails)
        if (flightDetails are available) do:
            main requests database (D) to SELECT available flights
            database returns available flight data
            main shows available flights to Guest
        else do:
            main requests database (D) to SELECT available flights
            database returns NULL
            main redirects Guest to DetailsPage (DP)
            DP prompts Guest to correct flightDetails
        end

END FUNCTION
```
