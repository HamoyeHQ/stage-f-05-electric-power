Hamoye Data science Community Project
Copyright (c) 2020

Recommended Use: Regression/Clustering Models
Domain: Electricity

# HOUSEHOLD ELECTRIC POWER CONSUMPTION DATA SET

This data set has 2075259 rows and 9 columns.
This dataset provides measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years.
Different electrical quantities and some sub-metering values are available. The Following data dictionary gives more details on this data set:

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

**Note:**
*(Global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3), represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3.

**Acknowledgement**
This data set has been sourced from https://www.kaggle.com/uciml/electric-power-consumption-data-set. The contributors to this project are as follows:
