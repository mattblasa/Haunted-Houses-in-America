# Haunted Places

This repository contains code for scraping, cleaning and geocoding data from [The Shadowlands Haunted Places Index](http://www.theshadowlands.net/places/).
Currently this dataset only contains the US locations.
The non-US places don't have a standard schema and will be a challenge to scrape.

## The Dataset

The dataset itself is a CSV file with the following columns:

| column         | type   | description                                                  |
| -------------- | ------ | ------------------------------------------------------------ |
| description    | string | A textual description with details of the haunting.          |
| location       | string | A more detailed description of the haunted place's location. |
| longitude      | float  | The longitude of the location (geocoded dataset only).       |
| latitude       | float  | The latitude of the location (geocoded dataset only).        |
| city           | string | The city of the haunted place.                               |
| city_longitude | float  | The longitude of the city (geocoded dataset only).           |
| city_latitude  | float  | The latitude of the city (geocoded dataset only).            |
| state          | string | The state of the haunted place.                              |
| state_abbrev   | string | The abbreviated state.                                       |
| country        | string | The country of the haunted place. Currently only US.         |

## Original Source: 
Orginally scraped by Timothy Renner, with data orginally from theshadowlands.net.
<br>
https://github.com/timothyrenner/shadowlands-haunted-places
