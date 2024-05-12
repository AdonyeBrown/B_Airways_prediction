# Customer Empowerment and the Modern Buying Cycle

## Introduction
In the current digital era, customers are more empowered than ever. With a wealth of information available at their fingertips, consumer behaviour has transformed significantly. This shift has had a profound impact on the buying cycle, making it markedly different from what it used to be.

## The Empowered Customer
Today's customers have access to:
- Detailed product reviews
- Price comparisons
- Peer recommendations
- Extensive product information

This level of access means that customers are often well-informed and have high expectations from businesses and products.

## The Evolving Buying Cycle
The traditional buying cycle has evolved in response to this new customer empowerment. The stages of awareness, consideration, and decision are no longer linear but form a more dynamic journey as customers:
- Conduct their own research
- Seek out opinions and feedback
- Make informed decisions based on a variety of online sources

## Adapting to Change
Businesses must adapt to this new reality by:
- Providing transparent and comprehensive product information
- Engaging with customers across multiple platforms
- Building trust through consistent and authentic interactions


## Overview
This project aims to predict the booking_complete(customers buying holidays) based on various features such as num_passengers, sales_channel, purchase_lead, length_of_stay, and flight_day using machine learning techniques. The objective is to achieve precise categorization that will assist in assessing customer behaviour.

## Dataset
The dataset used in this project includes the following attributes:

- **num_passengers**:  number of passengers travelling
- **sales_channel**: sales channel booking was made on
- **trip_type**: trip Type (Round Trip, One Way, Circle Trip)
- **purchase_lead**: number of days between travel date and booking date
- **length_of_stay**: number of days spent at destination
- **flight_hour**: hour of flight departure
- **flight_day**: day of week of flight departure
- **route**: origin -> destination flight route
- **booking_origin**: country from where booking was made
- **wants_extra_baggage**: if the customer wanted extra baggage in the booking
- **wants_preferred_seat**: if the customer wanted a preferred seat in the booking
- **wants_in_flight_meals**: if the customer wanted in-flight meals in the booking
- **flight_duration**: total duration of flight (in hours)
- **booking_complete**: flag indicating if the customer completed the booking


## Features
- Exploratory Data Analysis (EDA) to understand the dataset.
- Feature Engineering to create new features that can aid in prediction.
- Model Selection to choose the best performing machine learning model.
- Model Evaluation to assess the accuracy of the predictions.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
To set up the project environment, run the following commands:
```bash
git clone https://github.com/AdonyeBrown/B_Airways_prediction.git
cd book-complete-prediction
pip install -r requirements.txt

## Conclusion
The empowered customer is here to stay, and the buying cycle will continue to evolve. Businesses that recognize and adapt to these changes will be better positioned to meet the needs of the modern consumer.