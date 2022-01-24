# Cryptocurrencies

Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. they are interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

##Results:
The first step we had to take was the preparation of the data, with out this we can't move on and expect our unsupervisor code to function properly. So we Preprocess the data using Data PCA follow up by reducing our Data dimensions. After preparing our data removing columns not needed for our analysis and removing any NAN from the data. Our next step was to find the number or range of K-Values needed, this would be our number of cluster used in our machine learning. We find this by using the common method of the K elbow curve as in the seen in the image below, after submitting our code our out put is a K-mean of 4. 
<img width="599" alt="Screen Shot 2022-01-23 at 7 48 26 PM" src="https://user-images.githubusercontent.com/90356052/150713882-2da33f18-7481-4d48-8e94-db182c5313aa.png">

Data was combined and a 3D-scatter plot was made with the PCA data and the clusters:
<img width="599" alt="Screen Shot 2022-01-23 at 7 53 46 PM" src="https://user-images.githubusercontent.com/90356052/150714378-98080aef-c40b-45f6-94ca-625c7d42174c.png">

Finally, a hvplot.scatter plot was created using x=Total Coins Mined and y=Total Coin Supply:

<img width="599" alt="Screen Shot 2022-01-23 at 7 54 25 PM" src="https://user-images.githubusercontent.com/90356052/150714444-7370a23e-56eb-4114-9a7d-934e8f8883fc.png">
