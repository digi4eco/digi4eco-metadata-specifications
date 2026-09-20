## version 1.0.8 ##
* Synced with the EMSO ERIC metadata specifications: added `goos_passport_id`, removed `wsi_platform_code`
* Removed the EMSO-specific global attributes `emso_regional_facility_uri`, `emso_regional_facility_name`, `emso_site_uri` and `emso_site_name`
* Removed the EMSO-specific platform attributes `emso_platform_name` and `emso_platform_uri`
* Removed the now unused `oso_ontology_uri` and `oso_ontology_name` compliance tests
* External resources are now served from the DIGI4ECO repository instead of the EMSO ERIC one

## version 1.0.7 ##
* Change `projects` to `project` to align with [ACDD](https://wiki.esipfed.org/Attribute_Convention_for_Data_Discovery_1-3)
* Add `project_uri` to provide normative links to project descriptions
* Change `project_codes` to `project_code` to maintain consistency in terms (use singular)

## version 1.0.6 ##
* Allow multiple DOIs for the same dataset

## version 1.0.5 ##
* Add `keywords_uri` and `keywords_type`
* Adding `time_end` P01 code

## version 1.0.4 ##
* Adding proper keywords and data processing levels documentation
* fixing mess in git history

## version 1.0.3 ##
* * changing `doi`, keywords,  `keywords_vocabulary`  and `keywords_vocabulary_uri` from optional to mandatory
* adding `time_end` as an optional coordinate
* adding Data Processing Levels to the specifications
* Changing Copernicus codes from a list in json to a human readable Markdown file

## version 1.0.2 ##
* Renaming `contributors` to `contributor_names` to make it aligned with OceanSITES
* Adding 

## version 1.0.2 ##
* Fixing overwriting issues in resources.json, now CSV files are properly stored and related.json files are correctly produced

## version 1.0.1 ##
* Adding DIGI4ECO_Metadata_Specifications.md to the resources.json manifest file

## version 1.0.0 ##
* 100% alignment with Climate and Forecast
* Adding mandatory coordinates time, depth, latitude, longitude, sensor_id, platform_id
* Adding `variable_type` to explicitly declare the role of each variable
* Force the same dataset format regardless of NetCDF or ERDDAP
* Integrating OSO ontology
* Adding `external-resources` to centralise file downloads from the metadata harmonizer
* ... and many more changes