# Servlet-based-web-application

The feature of Homehub

    	2.1 User Account/Profile/Transaction management & MySQL
			We have implemented the MySQL database to store all the user registration details including customers and manager, with attributes like username, 
      password and user type.
			MySQL database is also implemented with the user profile data, which includes username, user address: street, state, zip code, contact information: 
      phone number and email.
			Transactions with MySQL database in both service order and product order, with essential information like order id, user information: user name, 
      address, phone, delivery method and payment, product information: product id, price and quantity.
      
		2.2 Recommender
			We trained MySQL data and NoSQL data of a user behavior to do a product recommendation function, which would pop up when a user tends to check out.
      
		2.3 Twitter matches
			We registered a Twitter API to catch the twitter streaming data to match any product on our website and show them on the home page.
      
		2.4 Analytics & Visual Report
		  Analytics and the visual report are available on the manger page, which shows the inventory or sales report with proper bar charts. A Manager is able to 
      use these visual data to develop any sorts of business idea.
      
		2.5 Reviews & Trending & MongoDB
			Reviews including services review and product reviews are all working with MongoDB. After then, we also use the review as a base to implement the trending 
      function, which returns a list of the most liked product, the most sold product and the most popular zip code in our database.
      
		2.6 Auto-Complete Search feature
			We have set up the auto-complete feature that directly loads the data from MySQL, when a user is typing, it would show the auto-complete information of 
      products from the database.
      
		2.7 Google MAPS - Near ME search feature
			We used the Google Map API on the home page for allowing users to find the nearest service based on the keyword input and the current location of the user.
      
		2.8 Knowledge Graph Searches & Neo4J
			We convert the mysql database to a csv file, and then import it to the graph database, neo4j. We built the database like Blue dot as a customer PLACED, 
      brown dot as order CONTAINS pink dot as product DELIVER TO green dot zip code or PICKUP AT dark pink dot as store location. Cypher of Neo4j is also 
      suitable for doing queries like an easy way to find the customer who spent the most money.

		2.9 Java E-mail feature
			We use JavaMail API and Java Activation Framework on store manager page,once a manager sends the message to the customer, customers will receive the email 
      in their mailbox.
