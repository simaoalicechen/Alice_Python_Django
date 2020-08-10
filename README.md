# Full-Stack-Web-Development-Python-Django

This Web Application builds an interactive real estate website with personalized Frontend and robust Backend support. Here is a breakdown of the detailed apps: 

Frontend: 
1. The Page App includes personalized web layout and design to better match the client's requests and needs. It contains Index, About and inter-linked pages with listings' urls and templates for future apps; 
2. The Listings App includes listings info in both one page and seperate pages. It allows the users to search the listing based on various criteria, including price, sqft, # of bathroom, # of bedroom, city, and state. Each listing page shows realtor's info; 
3. The Realtor App includes realtor contact info and allows users to contact them. The inquiries will be stored in the PGAdmin database; 
4. The Accounts App allows the users to register, login, and logout. It provides a personalized Dashboard page and functionality to different users, where they can access their saved searches and previous inquiries with realtors; 
5. The Contacts App allows the users to connect with the realtors on the webpage, and any inquiries with be automatically saved in the database and send to the users' and realtors' emails. They will be saved to the users' dashboard if the users choose to register; 
6. The alert messages will appear each time the users interact with the website, including Error messages, Success messages, and they will automatically disappear within 3 seconds; 

Backend: 
The web app uses Postgres and PGAdmin to run and maintain the database that contains the listings', accounts', users', realtors' informtaion and communication history. It also has the feature to send emails to related parties whenever communication occurs.
