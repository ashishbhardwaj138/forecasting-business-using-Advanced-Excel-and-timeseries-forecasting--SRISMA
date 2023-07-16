# forecasting-business-using-Advanced-Excel-and-timeseries-forecasting--SRISMA
There are some machines from which policies are made. Each month, new mahines are set up and we have a cummulative profit out of all. Based on the past data, we need to predict the business for the year 2016 and 2017
Input:										
	Sheet Name	Description								
	First	"Business Sourced from new insurance policies and Machines Installed month wise . 
Example: 
1) For business month Feb-09, there would be two records for machines installed in Jan-09 and Feb-09 with total policies sourced by policies installed in these months
2) For business month Dec-15, there would be 84 records for all past months (Jan-09 to Dec-15) installed machines as all these machines may have contributed to Dec-15 business"								
	Second	Year wise Average Premium / policy								
	Third	Month wise total machines installed								
	Assumption	List down all your assumptions in this sheet here								
	Simulation	Build a formula based simulation for the end user, where he provides inputs and get the business output								
	Challenge	Asnwer three Questions based on given scenarios using your simulation model								
										
Expectation:										
	1) Develop a excel based simulation to forecast the total business in next two years (2016 & 2017)									
	2) Provide answers to all questions mentioned "Challenge" sheet									
										
Rules:										
	1) Submit this file as your submission									
	2) Simulation sheet must be formula based so that user can play with key metric (Total number of Machines andAverage Premium per policy) to see tha impact									
										
Learning:										
	In this competition, you will learn how to take a business problem, make simplifying assumptions and build simulation models for critical business decisions.
 Total Business = ((Total Previous Years Machine * Number of Policy Per Previous Year Machine) + (Total New Machines * Number of Policy Per New Machine)) * Average Premium Per Policy		
 For predicting business, 
 1	Calculate MOM Number of Policies Per Machine	Total New Policies /Machines Installed	
2	Monthly Business	Machines Installed in Current Month * Number of Policies Per New Machine* Average Premium Per Policy	
3	Forecast MOM Total New policies and Total Machines 		
4	Aggregate Total Machines on annual basis, if that within cap quantity, safe.		
5	otherwise, obtain the pivot table of total machines data with rows as Year and Month as columns and sum of total machines as values		
6	forecast these monthly production to year 2016 and 2017.		
7	now, take all these values as percentage of total , this will represent percentage distribution of total machines throughout the year		
8	multiply the 2016 and 2017 rows monthly data with 65000 to obtain adjusted monthly business.		
![image](https://github.com/ashishbhardwaj138/forecasting-business-using-Advanced-Excel-and-timeseries-forecasting--SRISMA/assets/85213381/ca53c6cb-53e7-4554-8ff3-2b8b0872be83)

![image](https://github.com/ashishbhardwaj138/forecasting-business-using-Advanced-Excel-and-timeseries-forecasting--SRISMA/assets/85213381/22f7a106-ba0f-49f3-9254-f3d358c89809)

![image](https://github.com/ashishbhardwaj138/forecasting-business-using-Advanced-Excel-and-timeseries-forecasting--SRISMA/assets/85213381/188e97a8-2c18-4d81-bd55-5565345fe6ac)

