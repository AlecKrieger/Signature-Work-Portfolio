# Signature-Work-Portfolio
Signature Work Portfolio

Database Microbialite
Repositories: https://github.com/AlecKrieger/Microbialite_BackEnd and https://github.com/AlecKrieger/Microbialite_Frontend

This project was made for my database class. It is a full stack CRUD applications made to record Microbialite research data. For the project we were given an Access database made by the professor conducting the research and we normalized the data into new relations and migrated some of it into our database. We recreated the reports from the original database in SQL. The advantage of using SQL over Microsft Access is that SQL scales better and can be linked to larger applications.

We made this project in a week so some features, especially in the front end are unfinished. I still had a lot of fun with this project. It incorporated libraries and frameworks like FastAPI and React that I've wanted to use to create a larger project with for a while. I learned a lot from doing this project.

Domain-Viewpoint: One of the client's reason for upgrading his database system was to facilitate research amongst a larger team of student researchers and collaboration with other researchers. This isn't possible with Microsoft Access because each is its own seperate instance. This means that if a researcher updates their own file it won't propogate to other files. We decided to make a web application because it seemed like the easiest way to facilitate information sharing. Research added to the database can be viewed or updated by anyone with the correct credentials.

Crime Website

Repositories https://github.com/line7313/webdev-rest

This was our most recent project in Web Development. We recieved a crime database and created a full stack web application that can create, read, and delete crime reports. The website uses a map made leaflet to display St Paul's 17 nieghborhoods and the number of crimes within each. We used nominatim to locate specific crimes on the leaflet map by looking up the obfuscated address in the API and dislaying a marker at the returned coordinates. I had significant trouble working with leaflet because the map markers don't stay in one spot when the user zooms in and out on the map. This was a group project in collaboration with two other people. I wrote the PUT route method on the backend and implemented all of the map features on the front end.

Webdev-Dynamic
Repositories: https://github.com/ethan-lott01/webdev-dynamic

This project was another project for my Web Development class. We were assigned to create a website that displayed data from a dataset related to environmental sustainability. I found a dataset on Keggle that related to energy use and production from a wide varitety of fuel types including fossil fuels like coal, oil, and natural gas along with renewables like wind and solar in Spain. I contributed heavily to the project. I set up the SQLITE database, wrote the queries for the different pages, set up the table to dynamically display the columns returned from the query, and embedded the graph using a script CDN.
