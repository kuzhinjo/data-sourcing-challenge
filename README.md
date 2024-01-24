# Data sourcing through various APIs

### 1. Access New York Times Movie Database through API 
* Any article search API calls after 5 was getting policy violation error from NYT. So the number of calls limited to less than 5 pages in the code.

* Extract the movie tittle from the API.

### 2. Access TMDB Movie Database through API 
#### Extract below details from TMDB API response<br> 
* Genre
* Spoken Languages 
* Production Countries

### 3. Merge the above two data frames, clean the data and export as CSV