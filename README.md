# Academic Project: Hotel Booking Prediction and Data Warehousing

## Project Overview

This academic project focuses on the analysis and prediction of hotel bookings using structured data organized in a data warehousing format. The work combines data manipulation, exploratory analysis, and machine learning techniques to understand booking behavior and support prediction tasks related to hotel reservations.

The project is implemented using Python in a Jupyter Notebook and relies on fact tables provided in the project ZIP file, structured to support analytical and predictive use cases in the hotel booking domain.

---

## Hotel Booking Context

The dataset models hotel booking operations, including reservations, customers, dates, and booking outcomes. The objective is to analyze historical booking data and use it to support prediction tasks such as booking volume trends, cancellation behavior, or demand patterns.

The data structure follows a fact-based analytical design commonly used in decision support systems.

---

## Fact Tables Included

The ZIP file contains fact tables representing measurable hotel booking events. These fact tables serve as the core of the analytical and predictive workflow.

Typical fact tables included in this context are:

* FactBooking
  Stores booking-level transactional data such as booking identifiers, stay duration, number of guests, booking status (confirmed or canceled), and monetary measures related to hotel reservations.

* FactReservationActivity
  Captures reservation-related events over time, supporting analysis of booking creation, modification, and cancellation patterns.

* FactHotelPerformance
  Aggregates booking measures at the hotel level, enabling analysis of occupancy rates, booking volume, and overall performance indicators.

Each fact table is linked to descriptive dimensions (such as date, customer, hotel, or room type) and is designed to support analytical queries and machine learning feature extraction.

---

## Role of Fact Tables in Prediction

The fact tables are used as the primary data source for hotel booking prediction tasks. They provide:

* Quantitative measures used as model inputs
* Historical patterns for supervised learning
* Aggregated indicators for trend analysis
* Structured features for machine learning pipelines

Data extracted from these fact tables is cleaned, transformed, and prepared before being used in predictive models.

---

## Data Manipulation and Machine Learning

The Jupyter Notebook applies the following steps using the fact tables:

* Loading fact tables into data frames
* Data cleaning and preprocessing
* Feature selection derived from booking measures
* Exploratory analysis of booking behavior
* Training and evaluation of machine learning models
* Interpretation of predictive results in a hotel booking context

---

## Tools and Technologies

* Python
* Jupyter Notebook
* Pandas and NumPy for data manipulation
* Matplotlib and Seaborn for visualization
* Scikit-learn for machine learning
* Fact-based data modeling for analytical support

---

## Academic Value

This project demonstrates:

* Use of fact tables in a hotel booking decision-support context
* Integration of data warehousing concepts with machine learning
* Practical application of data manipulation for predictive analytics
* Understanding of hotel booking dynamics through structured data

---

## Conclusion

By organizing hotel booking data around fact tables and applying machine learning techniques, this project provides a structured and academically grounded approach to hotel booking prediction. The use of fact tables ensures analytical clarity, scalability, and relevance to real-world decision-making scenarios in the hospitality industry.
