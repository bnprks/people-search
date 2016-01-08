# People Search

This project was created as a faster version of Princeton's internal student directory. It's notable design choice is that it downloads all the student data to the client so that searches can be executed instantly as the user types. The site with current data is available [here](http://princetonfacebook.com) with a Princeton student login, but the public demo uses fake generated data.

Although it was originally written with React, I remade the site using plain JS because of performance concerns for the instant search and infinite scrolling. Because the tool is so simple the code stayed a similar length to the React version.
