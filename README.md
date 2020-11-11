Hamoye Data science Community Project
Copyright (c) 2020

# Kaggle Project Statement

* Often times, we always ask how do these National Electricity Distribution agencies measure and generate the bills the serve to their customers. Out of our inquisitive nature as man, we would realy like to know. It is not rocket science - because our bills are generated based on energy consumption in our household over a given period of time. So, how can i know what contribute to most energy consumption in my household? This is an important question that requires a holistic answer.

* Context: Measurements of electric power consumption in one household<b> with a one-minute sampling rate over a period of almost 4 years.</b> Different electrical quantities and some sub-metering values are available.

## Project Aim

* Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

# DATA DESCRIPTION

### Data Set Characteristics:
Multivariate, Time-Series

### Associated Tasks:
Regression, Clustering

## Data Set Information:
Data Set Information:

This archive contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months).

Notes:

1. (global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.

2. The dataset contains some missing values in the measurements (nearly 1.25% of the rows). All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.

[Source](http://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)


### Attribute Information:
1. date: Date in format dd/mm/yyyy

2. time: time in format hh:mm:ss

3. globalactivepower: household global minute-averaged active power (in kilowatt)

4. globalreactivepower: household global minute-averaged reactive power (in kilowatt)

5. voltage: minute-averaged voltage (in volt)

6. global_intensity: household global minute-averaged current intensity (in ampere)

7. submetering1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).

8. submetering2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.

9. submetering3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

### DATA UNITS EXPLANATION
1. date and time: The date format is yyyy-mm-dd and time format is HH:MM:SS. The data point interval is reported every mins as average of all measurement taken within a min.
   
2. globalactivepower: This is measured in kilowatt i.e 1000watts. watts is unit of power and power energy expended per unit time.
   
3. global reactivepower: This is measured in kilowatt i.e 1000watts. watts is unit of power and power energy expended per unit time.
   
4. volt: Volt is unit of voltage - which tells the electric potential difference between two point in a conductor carrying current.

5. watt-hour: This measure of energy accross various appliances.


### Data Source Climate
The climate of Paris and the region of Île-de-France is temperate and influenced by the Atlantic Ocean: it is quite cold but not freezing in winter and pleasantly warm in summer. However, it has some continental characteristics too, so it can sometimes be very cold in winter and hot in summer.

# Possible Project Objective
* I think you can do some time series forecasting with this dataset. For instance you could have fun trying to predict the active power consumption for the next N minutes given the consumption for the p former minutes. p is a hyper parameter of your model ( window width ).

[Source](https://www.kaggle.com/uciml/electric-power-consumption-data-set/discussion/126949)

**Data Dictionary:**

<!DOCTYPE html>
<html>
    <head>
        <style>
             table, tr, th, td {
                border-collapse: collapse;
                border: 2px solid black;
                text-align: center;  
            }
        </style>
    </head>
    <body>
<table>
          <tr>
            <th><b>Column Position</b></th>
            <th width="150"><b>Attribute Name</b></th>
            <th><b>Definition</b></th>
            <th><b>Data Type</b></th>
            <th><b>Example</b></th>
            <th><b>%Null Ratios</b></th>
          </tr>
          <tr>
            <td>1</td>
            <td>Date</td>
            <td>Date: Date in   format dd/mm/yyyy</td>
            <td>Quantitative</td>
            <td>16/12/2006, 10/5/2007, 24/9/2007</td>
            <td>?</td>
          </tr>
          <tr>
              <td>2</td>
              <td>Time</td>
              <td>Time: time in   format hh:mm:ss</td>
              <td>Quantitative</td>
              <td>17:27:00, 6:56:00, 10:00:00</td>
              <td>?</td>
          </tr>
          <tr>
              <td>3</td>
              <td>Global_Active_Power</td>
              <td>Global_active_power:   Household global minute-averaged active power (in kilowatt)</td>
              <td>Quantitative</td>
              <td>4.216, 5.412, 3.488</td>
              <td>?</td>
          </tr>
          <tr>
              <td>4</td>
              <td>Global_Reactive_Power</td>
              <td>Global_reactive_power: Household global minute-averaged reactive power (in kilowatt)</td>
              <td>Quantitative</td>
              <td>0.418, 0.47, 0.228</td>
              <td>?</td>
          </tr>
          <tr>
              <td>5</td>
              <td>Voltage</td>
              <td>Voltage:   Minute-averaged voltage (in volt)</td>
              <td>Quantitative</td>
              <td>234.84, 232.78, 233.06</td>
              <td>?</td>
          </tr>
          <tr>
              <td>6</td>
              <td>Global_Intensity</td>
              <td>Global_intensity:   Household global minute-averaged current intensity (in ampere)</td>
              <td>Quantitative</td>
              <td>18.4, 23.2, 15</td>
              <td>?</td>
          </tr>
          <tr>
              <td>7</td>
              <td>Sub_Metering_1</td>
              <td>Sub_metering_1:   Energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to   the kitchen, containing mainly a dishwasher, an oven and a microwave (hot   plates are not electric but gas powered).</td>
              <td>Quantitative</td>
              <td>1, 38, 17</td>
              <td>?</td>
          </tr>
          <tr>
              <td>8</td>
              <td>Sub_Metering_2</td>
              <td>Sub_metering_2:   Energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to   the laundry room, containing a washing-machine, a tumble-drier, a   refrigerator and a light.</td>
              <td>Quantitative</td>
              <td>1, 36, 5</td>
              <td>?</td>
          </tr>
          <tr>
              <td>9</td>
              <td>Sub_Metering_3</td>
              <td>Sub_metering_3:   Energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to   an electric water-heater and an air-conditioner</td>
              <td>Quantitative</td>
              <td>17, 0, 18</td>
              <td>?</td>
          </tr>

  </table>
  </body>
  </html>


**Acknowledgement**
This data set has been sourced from https://www.kaggle.com/uciml/electric-power-consumption-data-set. The contributors to this project are as follows:
