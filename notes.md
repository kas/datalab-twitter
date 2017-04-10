# notes

## Getting all tweets from a city

## Twitter API
* API limits
  * Certain # of tweets in 15 minutes
  * Search API only gives you tweets within the last 7 days
    * May not be a complete index
* Can set location filter for Streaming API(?) and Search API(?)
* Use geo/search API to get the place id, then perform regular search (or Streaming API) using `place:place_id`
* Three APIs?
  * Search
  * Streaming
  * "firehose"
* Search by city in user's profile?
* v1.1 of the `POST statuses/filter` API has a locations parameter
  * Only works on geolocated tweets
  * Does not care about the 'location' tweet field which is user-filled
* User must have location enabled for tweets
  * Phone GPS
* User has 'from' field in their profile
* Streaming API
  * locations
    * longitude,latitude pairs specifying a set of bounding boxes to filter tweets by
    * The user's location field is not used to filter tweets

## Scraping via Scrapy and Selenium
