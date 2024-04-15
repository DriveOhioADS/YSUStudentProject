# DriveOhio Project README

### What did we build?

Over the spring semester, we built a system of files wherein we can access DriveOhio's DynamoDB database, query for specific topics, clean and manipulate data, and output automatically logged disengagements, heatmaps, standard deviations of satellite strength, and more.

#### What do I need to make it work?

##### Function Input

The files will take a list of groupMetadataIDs, built from a csv ile that you will run later in the mandatory first steps.

##### Packages, Installs, Downloads

git (?) to clone repository.

Firstly, python 3.10.+ is required to be installed to make this work.

Then, you will need to install the necessary python packages to get the code running, which is available on our project github page.

Everything required to run the code is now installed.

##### Mandatory first steps

There is however, an order in which things must be run to have full functionality.

We recommend you run the

"gmIDTracking.ipynb" file to obtain a list of all groupMetadataIDs - **FIRST**

Then, we recommend you run the

"massDataQuery.ipynb" file next to obtain all the data.

This will query and store the data in a new folder which will allow you to reuse the data later on if you'd like to do more investigation instead of needing to requery.

##### Helper Functions

#### How does the function work?

The overall ecosystem behaves in the following manner:

- Setup groupMetadataID list, tells us what to target in the database and what we want to view
- Query and store this data on our local machine
- Clean, manipulate, and add new necessary columns (transitions, driver notes, weather, route) to this data
- Branches in whatever direction you want to do with the final dataframe (mapping, logging, etc)

#### What should I expect?

Whatever specific end file you run you can expect the output of that whether it be visualizations, etc.


##### Output description


Mapping - dash maps that will show the data you request

Logging - an excel file with automatically logged screenshots, start/stop points of disengagement

Heatmap - Map of points of disengagements
