




# 911 Calls Analysis Project

## Overview
This project analyzes emergency 911 call data from Montgomery County, PA to uncover patterns and insights in emergency response needs. Using Python and key data science libraries, I explored various aspects of emergency calls including timing, reasons, and geographic distributions.

## Key Features
- Analysis of 663,522 emergency calls from 2015-2020
- Visualization of call patterns by time of day, day of week, and month
- Breakdown of emergency types (EMS, Traffic, Fire)
- Heat map analysis of call volumes
- Temporal pattern identification

## Python Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights
- EMS calls were the most frequent (332,692 calls)
- Traffic incidents were second most common (230,208 calls)
- Fire-related emergencies were third (100,622 calls)
- Call volumes were consistently lower during weekends
- Peak call times occurred during late afternoon hours on weekdays
- Lower call volumes observed during holiday seasons

## Dataset
The data comes from Montgomery County, PA and contains the following fields:
- lat: Latitude
- lng: Longitude
- desc: Description of emergency call
- zip: Zipcode
- title: Title/type of emergency
- timeStamp: Date and time of call
- twp: Township
- addr: Address
- e: Dummy variable (always 1)

## Future Improvements
- Geographical visualization of emergency calls
- Predictive modeling for call volumes
- Response time analysis
- Seasonal trend analysis

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Authors

- [@octokatherine](https://www.github.com/octokatherine)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Running Tests

To run tests, run the following command

```bash
  npm run test
```

