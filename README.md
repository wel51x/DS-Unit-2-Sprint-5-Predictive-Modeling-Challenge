# Winston's README

# Predicting the Status of Water Pumps in Tanzania

The file water_pumps_project.ipynb contains the project notebook.

#### Summary
Using data from Taarifa and the Tanzanian Ministry of Water, I predicted which pumps are functional, which need some repairs, and which don't work at all. The features are mainly based on a number of variables about what kind of pump is operating, when it was installed, and how it is managed. A smart understanding of which waterpoints will fail can improve maintenance operations and ensure that clean, potable water is available to communities across Tanzania.

This predictive modeling challenge comes from DrivenData, an organization who helps non-profits by hosting data science competitions for social impact. The competition has open licensing: "The data is available for use outside of DrivenData." The data comes from the Taarifa waterpoints dashboard, which aggregates data from the Tanzania Ministry of Water. Taarifa is an open source platform for the crowd sourced reporting and triaging of infrastructure related issues. 

#### File descriptions
* train_features.csv : the training set features
* train_labels.csv : the training set labels
* test_features.csv : the test set features
* sample_submission.csv : a sample submission file in the correct format

#### Features
The goal was to predict the operating condition of a waterpoint for each record in the dataset provided the following set of information about the waterpoints:

amount_tsh : Total static head (amount water available to waterpoint)

date_recorded : The date the row was entered

funder : Who funded the well

gps_height : Altitude of the well

installer : Organization that installed the well

longitude : GPS coordinate

latitude : GPS coordinate

wpt_name : Name of the waterpoint if there is one

num_private :

basin : Geographic water basin

subvillage : Geographic location

region : Geographic location

region_code : Geographic location (coded)

district_code : Geographic location (coded)

lga : Geographic location

ward : Geographic location

population : Population around the well

public_meeting : True/False

recorded_by : Group entering this row of data

scheme_management : Who operates the waterpoint

scheme_name : Who operates the waterpoint

permit : If the waterpoint is permitted

construction_year : Year the waterpoint was constructed

extraction_type : The kind of extraction the waterpoint uses

extraction_type_group : The kind of extraction the waterpoint uses

extraction_type_class : The kind of extraction the waterpoint uses

management : How the waterpoint is managed

management_group : How the waterpoint is managed

payment : What the water costs

payment_type : What the water costs

water_quality : The quality of the water

quality_group : The quality of the water

quantity : The quantity of water

quantity_group : The quantity of water

source : The source of the water

source_type : The source of the water

source_class : The source of the water

waterpoint_type : The kind of waterpoint

waterpoint_type_group : The kind of waterpoint

#### Labels
There are three possible values:

functional : the waterpoint is operational and there are no repairs needed

functional needs repair : the waterpoint is operational, but needs repairs

non functional : the waterpoint is not operational
