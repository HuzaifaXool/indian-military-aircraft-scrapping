# indian-military-aircraft-scrapping
Indian Military Aircraft Scrapping

## Introduction

This project aims to create a dataset of the names and countries of origin of active Indian military aircraft by scraping data from the (https://en.wikipedia.org/wiki/List_of_active_Indian_military_aircraft). The extracted data can be used for various analytical purposes, research, and visualizations.

## Features

- Extracts the names of the aircraft and their countries of origin.
- Handles missing or empty data by replacing them with 'None'.
- Outputs the data in a structured format (e.g., JSON, CSV)

## Data Structure

The scraped data is structured as a list of dictionaries, with each dictionary representing an aircraft. Each dictionary contains the following fields:

- `name`: The name of the aircraft.
- `country`: The country of origin of the aircraft.


## Example Output

### Example CSV Output

The following is an example of the CSV output:

```csv
Name,Country
"Dassault Rafale","France"
"HAL Tejas","India"
"Sukhoi Su-30MKI","Russia"
"Mikoyan MiG-29","Soviet Union"
"Dassault Mirage 2000","France"
"SEPECAT Jaguar","United Kingdom"
