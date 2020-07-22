# whatmovie
I am currently in the process of porting my old php based website to a NodeJS website using Javascript to access an API rather than php. The website consisted of different options including; 

Movie Search; Search for movies using the "tmovieDB" this will return information about the movie including; year of release, description, title, similar movies and a trailer.

Movie Highlight; Shows movies that are currently showing in Cinema's and ones that are upcoming of interest to the user based on previous inputs. This is only a simple basing of users based off catagories like genre taking advantage of a horizontal asymptote.

Movie Reccomendation; This is the real showcase, this uses the mysql database in order to take information about a movie and corresponds it with the users preivous inputs and liking of a movie to then give a accurate number of movies decreasing in chance of likelihood as it goes down the list. This is based of the bayesian's approximation method of online ranking taking a very similar approch to AI.

Profile; The profile contains information where the individual can change their email, password, name and delete their account if they wish. It also shows their last login and when they signed up to the website.

The new database will be ported from mySQL to MongoDB and Dockerised. Additionally the php server will become a NodeJS setup using pug as the environment.
