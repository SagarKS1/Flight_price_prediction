Project Title: Flight_price_prediction

This is a Flask web app which predicts fare of Flight ticket.
![FPP](https://user-images.githubusercontent.com/81403919/139921546-5a937d4d-e40c-4cfe-882b-d7a9dc20476a.png)




Engineered features from the Departure Time, Date of Journey, to quantify the data and make it more understandable


Codes and Resources Used
Python Version: 3.8.5
Packages: pandas, numpy, sklearn, matplotlib, seaborn, flask, pickle
For Web Framework Requirements: pip install -r requirements.txt
Dataset: kaggle

Problem Statement
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same
flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are
so unpredictable. As data scientists, we are gonna prove that given the right data anything can be predicted. Here 
you will be provided with prices of flight tickets for various airlines between the months of March and June of
2019 and between various cities. Size of training set: 10683 records

Size of test set: 2671 records
1.FEATURES: Airline: The name of the airline.
2.Date_of_Journey: The date of the journey
3.Source: The source from which the service begins.
4.Destination: The destination where the service ends.
5.Route: The route taken by the flight to reach the destination.
6.Dep_Time: The time when the journey starts from the source.
7.Arrival_Time: Time of arrival at the destination.
8.Duration: Total duration of the flight.
9.Total_Stops: Total stops between the source and destination.
10.Additional_Info: Additional information about the flight
11.Price: The price of the ticket
