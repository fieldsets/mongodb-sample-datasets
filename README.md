# [MongoDB Sample Dataset](https://docs.atlas.mongodb.com/sample-data/available-sample-datasets/)

MongoDB does not provide any sample databases on their website, However, they do provide sample databases for their cloud service Atlas. These databases have been dumped from a MongoDB Atlas cluster using the MongoDB Compass GUI. There are 7 databases, with each database collection (table) stored in a seperate JSON file. These files will accelerate learning of the FieldSets data pipeline by allowing new developers to quickly experiment with prepopulated datasets.

## Installation

The CLI command `mongoimport` and the MongoDB database tools package need to be installed. You can find them [here](https://www.mongodb.com/try/download/database-tools?tck=docs_databasetools)

Using the [fieldsets-local](https://github.com/fieldsets/fieldsets-local) environment, setting the environment variable `MONGO_LOAD_SAMPLE_DATA=1`  will fetch all the necessary dependencies and data. You can use this sample data to quickly get started experimenting with the FieldSets data pipeline.

## Sample Datasets

| Dataset Name                                                                                | Description                                                       | Collections                                                                |
| ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [Sample AirBnB Listings Dataset](https://docs.atlas.mongodb.com/sample-data/sample-airbnb/) | Contains details on AirBnB listings.                              | listingsAndReviews                                                         |
| [Sample Analytics Dataset](https://docs.atlas.mongodb.com/sample-data/sample-analytics/)    | Contains training data for a mock financial services application. | accounts, customers, transactions                                          |
| [Sample Geospatial Dataset](https://docs.atlas.mongodb.com/sample-data/sample-geospatial/)  | Contains shipwreck data.                                          | shipwrecks                                                                 |
| [Sample Mflix Dataset](https://docs.atlas.mongodb.com/sample-data/sample-mflix/)            | Contains movie data.                                              | comments, movies, theaters, users                                          |
| [Sample Supply Store Dataset](https://docs.atlas.mongodb.com/sample-data/sample-supplies/)  | Contains data from a mock office supply store.                    | sales                                                                      |
| [Sample Training Dataset](https://docs.atlas.mongodb.com/sample-data/sample-training/)      | Contains MongoDB training services dataset.                       | companies, grades, inspection, posts, routes, stories, trips, tweets, zips |
| [Sample Weather Dataset](https://docs.atlas.mongodb.com/sample-data/sample-weather/)        | Contains detailed weather reports.                                | data                                                                       |

