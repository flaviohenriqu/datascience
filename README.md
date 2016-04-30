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
	
# Indoor User Movement Prediction from RSS Data

The dataset is available for download [here] (http://archive.ics.uci.edu/ml/datasets/Indoor+User+Movement+Prediction+from+RSS+data).

## Algorithm used: SVM (Support Vector Machine)

It is a classification method. In this algorithm, we plot each data item as a point in n-dimensional space (where n is number of features you have) with the value of each feature being the value of a particular coordinate.

The datasets were split into train and test data. I used 80% of data for training and 20% in the tests.

## Citation request:
D. Bacciu, P. Barsocchi, S. Chessa, C. Gallicchio, and A. Micheli, "An experimental characterization of reservoir computing in ambient assisted living applications", Neural Computing and Applications, Springer-Verlag, vol. 24 (6), pp. 1451-1464, doi:10.1007/s00521-013-1364-4, ISSN 0941-0643, 2014.