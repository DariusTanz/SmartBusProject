# SmartBusProject
testing
<<App Title = ToBus>>

This app was designed as a way to act as an intermediate between the user database(usually that includes all hardware :-)) and the workforce that is employed in a bus service providing firm.

	The apps main feature is to show the driver's behavior stats in a very descriptive manner .
The “USER INTERFACE ACTIVITY ” involves  the description of the driver and may other vital information such as 

1)No of passengers →from the sensors 	
	1.1)No of passengers boarded from each station
	1.2)How much money was credited to the bus
2)Driver speeding meter(represented as graph) // rash driving and stuff


The app also includes a google map API that provides the app with map with various functionalities
such as 

1)Provides google map API
2)Provide current user position(near real-time)
3)Provide current speed of object using google API
4)Pin point bus stops on the map 
	This feature serves as a dual purpose →one is to prevent the driver from stoping anywhere other than the bus stop →two,to give the driver with NAV feature through the app


App functionalities

// prelim  functionalities

1)User Sign-up
2)Update user details to the cloud database
3)User Login
4)Fetch user details from the stored cloud
5)Perform Auth

All the above stated functionalities are implemented to its fullest and works with 100% reliability. All the above stated feature was implementable with Google Firebase

//Secondary Functionalities

1)Fetch user details from cloud
2)Display them in the “User Interface Activity”
3)Plot the values from sensor readings that should have been uploaded to the cloud
4)Go to Map 

All the above stated functionalities are implemented to its fullest excluding feature  3.
Reasons:

1)The data from the sensors was not uploaded to AZURE database or any-other database for that matter. Hence without the data, plotting graph had fatal problems.

//Map Functionalities

1)Create Map Activity
2)Create live location function
3)Display live location details (graphical)
4)Pin point certain coordinates in the map 
5)Create a link able path to all pin pointed locations
6)Nav Feature

All the above stated functionalities are implemented to its fullest excluding features 4,5 and 6.
Reasons:
	Learning curve required more time than Expected

	Documentation

User Sign up Activity:

1)Enter User Credentials such as 
	1.1)Full Name
	1.2)Date of Birth
	1.3)Email 
	1.4)Create a password 
	1.5)Provide physical Application ID of the participant 
2)Press the “SIGN UP NOW ” button to create an account

User Login Activity:

1)Enter user Credentials
	1.1)USER NAME→ Email address provided
	1.2)PASSWORD  → password provided during sign up

User Interface Activity

The only intractable entity in this activity is the “GO TO MAP ”button.When this button is pressed it takes the users to the “mapsActivity”




