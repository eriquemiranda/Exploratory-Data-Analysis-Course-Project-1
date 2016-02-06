# Exploratory-Data-Analysis-Course-Project-1
Electric Power Consumption 

This is the Course Project 1 of Exploratory Data Analysis Course. This assignment uses data from the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets. In particular, we will be using the “Individual household electric power consumption Data Set” which I have made available on the course web site: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available. 

Plots
Plot 1: Histogram: Frequency of global active power in killowats
Plot 2: Plot global activer power by week day (plot legend in portuguese: qui (quinta-feira)=thursday, sex (sexta-feira)=friday, sábado (sáb)=saturday). I apologize for.
Plot 3: Sub_metering_1 (kitchen), 2 (laundry) and 3 (heater and air-conditioner), by datetime (week day).
Plot 4: Set of four plots with global active power, global reactive power, submetering 1 to 3, and minute-averaged voltage (in Volt) by datetime (week day).

Some conclusions

Taking into account: Active Power (in kW) is equal: P=Ui (Ampères) or (P(kW)=U (V)squared/R (ohms)).
Reactive power: this is the power that does not produce work, but it is necessary to produce the magnetic flux for the operation of those equipment.  
By means of Plot 1, I conclude that Global Active Power has a left skewed distribution (assymmetrical). Majority of frequency is lower than 2 killowats (lower consumption).
By means of Plot 2, I conclude that the overall active power distribution throughout the day is bimodal, higher at the beginning and end of the day.
By means of Plot 3, I conclude that the submettering 3 present a bimodal distribution, resembling the overall value and representing a significant portion of the global, submettering 1 present higher frequency only in a day of week and submettering 2 presenting a similar pattern of variation over time.
By means of Plot 4, I conclude a apparent inverse relashionship between Voltage and Global Active Power.There is not relationship between reactive power and datetime, but some peaks resembling the submettering 3 pattern.
