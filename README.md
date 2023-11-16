## Hotel-Booking-Problem-Analysis
Data Analysis Project

# Overview
Business problem: City hotels and resort Hotels are facing high cancellation rates. The aim of this project is to analyze the problem for lowering cancellation rate to increase efficiency in generating revenue.

Assumption: 
1. No unusual occurance happened
2. The biggest factor affecting the effectiveness of earning income is booking cancellation
3. Client make hotel reservation the same year they make reservation.

Hypothesis:
1. When the prices are higher , cancellation rates are higher also.
2. The majority of clients are coming from offline travel agents to make their reservation

# Data Sources
The primary dataset use for this analysis is the "hotel_booking.csv" file which contains information about city hotels and resort hotels.

# Tool
Python

# Data Cleaning And Exploratory Data Analysis
1. Data Loading and inspection
2. Checking the shape of dataset
3. Checking the column name and information
4. Checking the unique values
5. Handling null values
   

# Data Analysis & visualization
1. Finding the total percentage of cancellation rate and visualize it using bar chart and pie chart
2. Analysing the reservation status of both resort and city hotel in a single graph
3. Finding the cancellation rate of Resort Hotel
4. Finding the cancellation rate of City Hotel
5. Summarizing data to find the mean Average Daily Rate (ADR) for each reservation status date in the 'resort_hotel' & 'city_hotel' category to see the impact of price on cancellation rate
6. Analysing the reservation status for per month
7. Ploting the Average Daily Rate per month
8. ploting cancelation rate based on countries
10. Calculate the percentage distribution of market segments for canceled_data

# Result/Findings   
The analysis result are summerized as follows-
1. According to the reservation status analysis, resort hotels cancellation rate is higher than city hotel.
2. ADR of city hotel is less than resort hotel for some of the days. It can be the main reason that cancellation rate of resort hotel is higher than  city.
3. According to the reservation status per month, in january cancellation rate is highest but in August & September cancellation rate is lowest where reservation rate is highest August.
4. According to the 'reservation rate per month' and 'ADR per month' graph-
     * In September, ADR is lowest and Cancellation rate is also lowest
     * In Januray , ADR is highest and Cancellation rate is also highest
so it can be said that hotel room price has the direct impact on cancellation rate.
5. Portugal has the highest cancellation rate. so all the hotels PRT needs to take care of their systems and facilities and lower the rate of booking. They may advertise and run campaigns about their hotel to decrease the cancellatiion rate.
6. Maximum customer make their hotel reservation through online travel agents. Cancellation rate is also max for reservation through online travel agents. Maybe facilities that is mentioned in online do not match with reality thats why people cancel the reservation.

