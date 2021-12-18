# UMBC data_601_final_project
Maryland Statewide Vehicle Crashes Final Project 2020-2021

This project aims to explore areas in Maryland with the most accidents and to explore the possible contributing factors of accidents by doing preliminary Exploratory Data Analysis. 

The dataset is downloaded from opendata.maryland.gov and is cleaned specifically for analysis from 2020 through 2021
Maryland Statewide Vehicle Crashes: Crash data for Maryland from January 2015 through September 2021.
Maryland Statewide Vehicle Crashes — Person Details (Anonymized): Person data for Maryland vehicle crashes from January 2015 through September 2021.
Maryland Statewide Vehicle Crashes — Vehicle Details: Vehicle data for Maryland vehicle crashes from January 2015 through September 2021.

Below provides a glance what variables the data contains.

Maryland Statewide Vehicle Crashes: Crash data (16 variables)
YEAR (int64)
QUARTER (object)
LIGHT_DESC (object)
COUNTY_DESC (object)
COLLISION_TYPE_DESC (object)
SURF_COND_DESC (object)
REPORT_NO (object)
REPORT_TYPE (object)
WEATHER_DESC (object)
HARM_EVENT_DESC1 (object)
HARM_EVENT_DESC2 (object)
ACC_DATE (int64)
ACC_TIME (object)
LATITUDE (float64)
LONGITUDE (float64)
LOCATION (object)

Maryland Statewide Vehicle Crashes:  Anonymous Person Details (14 variables)
YEAR (int64)
Quarter (object)
SEX_DESC (object)
SEX_CODE (object)
INJ_SEVER_DESC (object)
REPORT_NO (object)
ALCOHOL_TEST_DESC (object)
ALCOHOL_TESTTYPE_DESC (object)
DRUG_TEST_DESC (object)
DRUG_TESTRESULT_DESC (object)
EJECT_DESC (object)
SAF_EQUIP_DESC (object)
DATE_OF_BIRTH (float64)
AIRBAG_DEPLOYED (float64)

Maryland Statewide Vehicle Crashes — Vehicle Details (9 variables)
YEAR (int64)
Quarter (object)
REPORT_NO (object)
HARM_EVENT_DESC (object)
VEH_YEAR (float64)
VEH_MAKE (object)
GOING_DIRECTION_DESC (object)
SPEED_LIMIT (int64)
HIT_AND_RUN_FLAG_DESC (object)

To run the python code, all you need is to install Python in your machine.  First to check whether you already have python, you can use the command below.
$python --version

To install Homebrew, type command below. 
$/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" 

To install Python 3, type
$ brew install python

Once you have everything installed, you can execute the python code by typing
$python tbd.py

This will generate a javascript file named tbd.js and a heatmap in HTML format for accident data points visualization. 

