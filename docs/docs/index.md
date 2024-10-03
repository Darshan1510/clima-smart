# clima-smart documentation!

## Description

ClimaSmart is a next-generation AI-powered weather prediction system designed to provide highly accurate, real-time weather forecasts alongside personalized recommendations. The system offers features such as Weather-Based Commute Suggestions, Outdoor Adventure Recommendations, and an interactive chatbot for real-time queries about weather conditions.

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://bucket-name/data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://bucket-name/data/` to `data/`.


