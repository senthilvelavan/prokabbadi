# ProKabbadi Hackathon

Prokabbadi Hackathon was aimed at predicting the below answers for the tournament

Task-1: Winner of the series 

	* Dabang Delhi K.C  

Task-2: Top team in the points table 
	
	* Dabang Delhi K.C 

Task-3: Team with most points for the successful raids 
	
	* Dabang Delhi K.C 

Task-4: Team with most points for the successful tackles 

	* Puneri Paltan 

Task-5: Team with the highest super performance total * 
	 
	* Bengal Warriors 

Task-6: Player with highest successful Raids %  
	
	* Saurabh Nandal (Bengaluru Bulls)

Task-7: Player with highes successful Tackles %

	* Lalit Chaudhary (Gujarat Fortune Giants)
	
# How was this accomplished

Broke down the task into multiple sub-tasks

1) Data Collection
	Data was collected using webscraping and webdriver (selenium) using python from official prokabbadi tournament website (https://www.prokabaddi.com/) for the below statistics
	Data was collected for each season (1 to 7) and also for all the seasons and then it was saved in a .csv file
	
		a) Team Stats
		b) Player Stats
		c) Match Schedule Stats
		d) PlayersInTeams
		e) DetailedTeamsAnalysis
		f) Team Standings
		
2) Prediction

	Task-1: Winner of the series 

		* Dabang Delhi K.C  
		
		Winner of the series was predicted using the historical playoffs that are played in the previous seasons and also considering the latest positions of the various teams
		in the current season. Simple machine learning models were used for predicting the winner (XGBoost)

	Task-2: Top team in the points table 
		
		* Dabang Delhi K.C 
		
		Top team in the points table was found by using the points data in the historical seasons and also for the current seasons. Historically, the teams are ranked from 1 to 12 and then it was found who scored the maximum points so that they end up as the top finishers in the table. Again, simple machine learning models were used (Gradient boost alogirthm)

	Task-3: Team with most points for the successful raids 
		
		* Dabang Delhi K.C 
		
		Team with the most points for the successful raids was also found using the historical data across all seasons and also during a particular season. Teams were ranked based on the most points for successful raids and then predicted using simple machine learning models

	Task-4: Team with most points for the successful tackles 

		* Puneri Paltan 
		
		Team with the most points for the successful tackles was also found using the historical data across all seasons and also during a particular season. Teams were ranked based on the most points for successful tackles and then predicted using simple machine learning models

	Task-5: Team with the highest super performance total * 
		 
		* Bengal Warriors 
		
		Team with the highest super performance total was computed using 4 different statistics provided was also found using the historical data across all seasons and also during a particular season. Teams were ranked based on the most points for successful tackles and then predicted using simple machine learning models

	Task-6: Player with highest successful Raids %  
		
		* Saurabh Nandal (Bengaluru Bulls)

	Task-7: Player with highes successful Tackles %

		* Lalit Chaudhary (Gujarat Fortune Giants)



	