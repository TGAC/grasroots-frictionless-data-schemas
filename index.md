# Frictionless Data for Field Trials

As part of the Grassroots Infrastructure, we have custom-built software for storing, editing and viewing the data from [Field Trial experiments](https://grassroots.tools/public/dynamic/fieldtrial_dynamic.html?type=AllFieldTrials). 
As well as having this, we expose the data as [Frictionless Data Packages](https://frictionlessdata.io/) for storing all of the data for an experiment together and in an open [FAIR](https://www.go-fair.org/fair-principles/) way. 
To represent this data we have created some [Frictionless Data Profiles](https://specs.frictionlessdata.io/profiles) for the different types of data. 
Our data hierarchy closely follows the [Breeding API (BrAPI)](https://brapi.org/) specification and an introduction into our standards is available in the [Grassroots Field Trial Service](https://grassroots.tools/docs/user/services/field_trial/index.md) web pages.

Currently we have the following profiles:

 * [Programme](https://grassroots.tools/frictionless-data/schemas/field-trial-programme-package.json)
 * [Field Trial](https://grassroots.tools/frictionless-data/schemas/field-trial-trial-package.json)
 * [Plots](https://grassroots.tools/frictionless-data/schemas/field-trial-plots-package.json)

We are also developing a [cross-platform stand-alone tool](https://github.com/TGAC/grassroots-client-frictionless-data) to extract the data from our Frictionless Data packages into convenient formats for people to use.



