# SortNumbers

Sort Application:
Sort a given amount of numerical values by randomly change position of the values in ascending orderTechnology Used:
Spring Tool Suite, Spring Boot,jsp, Java 1.8,h2 database
Setup and Run application:
Step to Setup and Run:
1.	Download and unzip the source repository for this guide or clone it using Git: git clone 
2.	Open Eclipse.
3.	Go to File -> Import
4.	Select Existing Maven Projects into Workspace and click on Next button.
5.Select the project and click on run as spring boot app or right click on SortNumbersApplication.java and select run as java application.
6.Hit application URL http://localhost:8443/
7.	Displays Sort Application page.
8.Enter the Unsorted Numbers 
9. Click Sort number button which will display the sorted numbers.
10.To test for the Negative scenario , for example enter 1, a and click on Sort Number button which will display the output as “Sort failed.”

To Persist the results i have used h2 database , but i got error in logging in to h2 console , so i was unable to create table and
persist the results , however i have written the code to save and get the results.

