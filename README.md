Over the past two decades, there has been a monumental shift in how people access
and consume video content. With universal access to broadband internet, numerous
platforms like YouTube, Netflix, and HBO Go emerged and steadily grew to prominence.
Although not a household name in itself, OTT is the exact technology that made the
streaming revolution possible.
OTT stands for Over The Top, refers to any video streaming service delivering content
to users over the internet, however there are subscription charges associated with the
usage of such platforms such as PrimeVideo, Netflix, HotStar, Zee5, Sony Liv etc. But
choosing your next movie to watch can still be a daunting task, even if you have access
to all the platforms.
“MyNextMovie” is a budding startup in the space of recommendations on top of various
OTT platforms providing suggestions to its customer base regarding their next movie.
Their major business is to create a recommendation layer on top of these OTT platforms
so that they can make suitable recommendations to their customers, however, since
they are in research mode right now, they would want to experiment with open-source
data first to understand the depth of the models which can be delivered by them.
The data for this exercise is open-source data which has been collected and made
available from the MovieLens website (http://movielens.org), a part of GroupLens
Research. The data sets were collected over various periods of time, depending on the
size of the set.
You have recently joined as a Data Scientist at “MyNextMovie” and plan to help the
existing team to set up a recommendation platform.
Dataset Link:
https://www.kaggle.com/code/ayushimishra2809/movie-recommendationsystem/data?select=ratings.csv
3
Objective:
1. Create a popularity-based recommender system at a genre level. User will input a
genre (g), minimum ratings threshold (t) for a movie and no. of
recommendations(N) for which it should be recommended top N movies which
are most popular within that genre (g) ordered by ratings in descending order
where each movie has at least (t) reviews.
Example:
Input:
➢ Genre (g): Comedy
➢ Minimum reviews threshold (t): 100
➢ Num recommendations (N): 5
Output:
2. Create a content-based recommender system which recommends top N movies
based on similar movie(m) genres.
Example:
Input:
S.No Movie Title Average Movie Rating Num Reviews
1 A 4.5 422
2 B 4.4 495
3 C 4.3 342
4 D 4.22 531
5 E 4.21 454
4
➢ Movie Title (t): Toy Story
➢ Num recommendations (N): 5
Output:
3. Create a collaborative based recommender system which recommends top N
movies based on “K” similar users for a target user “u”
Example:
Input:
➢ UserID: 1
➢ Num recommendations(N): 5
➢ Threshold for similar users (k): 100
