# Narmi Onsite Challenge

This is my initial implementation of the Narmi onsite challenge.
The full requirements of the challenge are described in the link below:

https://gist.github.com/chris-griffin/d01f7c98a77bec7d2473bf1c167682ed


## Running the Narmi Onsite Challenge
To run Narmi Onsite Challenge - run it from your favorite command line utility:
```
python3 narmi.py <filmFile>
```

Where <filmFile> is the file name of the master list of movies described in the link above.
**NOTE:** - the <filmFile> must be a .csv file with the format matching the above description. 

# Assumptions
Since this is a coding excercise performed under a limited timeframe, the goal initially is to get the implementation working, as described, with enough abstraction to add features to it continuously

# Future Improvements

* Add persistant storage. The initial implementation creates a schedule based on the input file, however, as "theatre owners" we would want to store our schedules to work on them later. This can be done either with file system storage, or better yet - through a web framework where we use a database to save our changes
* Add interactive options for the user. There is a wide variety of things that a movie theatre owner might want to adjust (start times, special events, etc). This can be achieved with more robust command line options, interaction with the user during runtime, or used when the app becomes a web app
* Support more "real life" movie theatre scenarios. For example - a blockbuster new release might take up multiple theatres and have the movie theatre facility itself stay open for longer than standard work hours; a theatre might rent out one of its screens to a private party for several hours, etc. 