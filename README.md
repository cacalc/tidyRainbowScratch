# tidyRainbowScratch
Scratch work for tidyrainbow https://github.com/r-lgbtq/tidyrainbow/

# The Movie Database Documentation
Disclaimer: This product uses the TMDB API but is not endorsed or certified by TMDB.

[Website](https://www.themoviedb.org/)

[API Documentation](https://developers.themoviedb.org/)

## About the Data
From the [website](https://www.themoviedb.org/about): 
>The Movie Database (TMDB) is a community built movie and TV database. Every piece of data has been added by our amazing community dating back to 2008. TMDb's strong international focus and breadth of data is largely unmatched and something we're incredibly proud of. Put simply, we live and breathe community and that's precisely what makes us different.

The data is pulled from the TMDB API using LGBT+ keywords, which then returned keywords used in the database. Most keywords were used for the final query, but a few were discarded due to not being relevant (e.g. - 'gender differences').

The keyword array is as follows: ['lgbt', 'gay', 'lesbian','transgender','bisexual','intersex','queer','genderqueer','non-binary','gender', 'asexual']

## Data Dictionary
* id - integer, unique ID
* title - string, title of record in English(?)
* original_title - string, unfortunately contains garbage characters because of non-English characters
* original_language - language of the record
* overview - string description of the record
* release_date - string
* popularity - number, popularity rating
* vote_average - number
* vote_count - integer
* adult - boolean, Boolean to indicate an adult movie.
* video - boolean - Boolean to indicate video.
* genre_ids - array[integer]
