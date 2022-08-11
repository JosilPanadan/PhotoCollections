# PhotoCollections
### Tech Assessment
## Project Description
This project is an API to call, combine, and return 2 API endpoints into a single HTTP response.<br>
The response is a combined collection of data from 2 endpoints. <br>
This API contains 2 operations.<br>
 1.return all the combined data from the two endpoints<br>
 2.return data relating to a single User Id. <br>
 ### Controllers and Methods used
 There is only one controller named as DataController.<br>
 There are three methods in DataController.<br>
  1.GetModel - To call the API endpoints to fetch its data.<br>
  2.GetDataDetailsAsync- The method which will combine the collection of data from 2 endpoints.<br>
  3.GetUserDetailsAsync- The method which will return data relating to a single User Id.<br>
  ## How to run the project
 1. Download the zip file to your local machine.<br>
 2.Compile and build it locally<br>
 3.Use Postman to test the API locally, use the local urls of the methods to see the output of the API<br>
 4.These are the example of local Urls to test the API<br>
   1.https://localhost:44356/api/data/GetUserDetails?UserId=9 // you can replce userID as you like <br> 
   2.https://localhost:44356/api/data/GetDataDetails <br>
## Project Requirements
1.Install .NET Core 3.1 
