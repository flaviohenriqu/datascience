# Data Science 

Example of Analysis Data using Pandas


## Data

1. Sample data used [here] (https://s3.amazonaws.com/ubee-public/data-samples/location_requests/north_america_sample.gz).

In this sample in csv format are approximately 20 million responses to location requests.
Each row consists of the following schema:

	"<mad_id>, <country>, <lat>, <lng>, <timestamp>, <source>"

at where:

	mad_id: single user identifier;
	country: acronym of the country of origin of the request. Can be "MX", "US" or "CA";
	lat: latitude of the geographical point of the request;
	lng: longitude from a geographical point of the request;
	timestamp: timestamp the time of the request, format: "EEE MMM d HH: mm: ss zzz yyyy" (eg "Thu Mar 24 14:08:08 BRT 2016")
	source: network technology in which location has been identified. Assumes values "GPS" or "wifi" in this sample.