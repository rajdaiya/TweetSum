# TweetSum

The scope of the system is set to social media sites, in particular a site called Twitter. Twitter is a micro blogging social media site that allows users to post frequent short messages also known as “micro blogs”. The content of such a site is an extraordinarily large number of small textual messages, posted by millions of users, at random or in response to perceived events or situations. These trends can be discovered using statistical analysis of mass of posts. The system has been developed to summarize the trending events or situations on Twitter in order to provide a quick overview of the generalized opinion shared by millions of users on that particular trend as it can be very tedious and humanly impossible to go through all the tweets on that trend. Also, users are likely to encounter spam, posts in other languages, rants, and other sources of misinformation. So the system provides the users with the generalized opinion of the people who have been talking on that topic through an automated generated summary by mapping the collected information on already available resources and thereby preserving context. The scope of this system involves:

•	Extraction: The tweets related to the trending topic from Twitter are extracted using existing Twitter API.

•	Filtration: The tweets extracted are filtered using algorithm(s) to remove spams, posts in other languages, rants, and other sources of misinformation.

•	Web-scraping: This component of the system deals with extraction of all the content related to the entered search term from the web.

•	Summarization: The tweets collected after filtration are mapped on pre-existing web-based via web scraping content to provide a generalized view which is then followed by summarization of top trending tweets to provide an overview of the opinions of twitter users.
