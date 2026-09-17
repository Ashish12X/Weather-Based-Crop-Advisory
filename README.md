# Weather-Based Crop Advisory System. 

## About the Project

Weather-Based Crop Advisory is a project that provides crop-related suggestions based on weather conditions.

Weather plays an important role in farming. Conditions such as temperature, rainfall, humidity and wind can affect activities like irrigation and spraying. The main purpose of this project is to combine weather information with crop information and provide simple and useful recommendations to the farmer.

The farmer can select a location and crop, after which the system gets the required weather information and checks the available advisory rules. Based on the weather conditions, the system displays a suitable crop advisory.

## Problem Statement

Farmers usually need to check weather information separately and then decide what action should be taken for a particular crop. General weather applications provide weather information but do not always give crop-specific recommendations.

This project aims to provide weather information together with simple crop-specific advisory messages so that the farmer can understand the possible impact of weather conditions on farming activities.

## Objectives

* To provide weather information for a selected location.
* To allow the farmer to select a crop.
* To use weather conditions for generating crop-related recommendations.
* To provide simple and understandable advisory messages.
* To show weather-related alerts when required.
* To provide an admin section for managing crops and advisory rules.

## Main Features

### Farmer

* User registration and login
* Select farming location
* Select crop
* Select crop stage where required
* View weather information
* Get crop-specific advisory
* View weather-related alerts

### Administrator

* Admin login
* Manage crop information
* Manage advisory rules
* Activate or deactivate advisory rules

## How the System Works

The basic working flow of the system is:

```text
Farmer
   ↓
Select Location
   ↓
Select Crop
   ↓
Get Weather Data
   ↓
Evaluate Advisory Rules
   ↓
Generate Crop Advisory
   ↓
Display Advisory to Farmer
```

For example, if a high probability of rain is detected, the system can provide an advisory to consider postponing irrigation when immediate watering is not required.

Similarly, if wind conditions are unsuitable for spraying, the system can display a recommendation to avoid pesticide or fertilizer spraying during that period.

## Advisory Rules

The system uses rule-based logic to generate recommendations.

| Rule | Weather Condition                 | Advisory                                                                  |
| ---- | --------------------------------- | ------------------------------------------------------------------------- |
| R01  | High probability of rain          | Consider postponing irrigation when immediate watering is not required.   |
| R02  | Unsuitable or strong wind         | Avoid pesticide or fertilizer spraying during unsuitable wind conditions. |
| R03  | Very high temperature             | Check soil moisture and irrigation requirements more frequently.          |
| R04  | High humidity with wet conditions | Increase attention to weather-related crop risk.                          |
| R05  | Weather data unavailable          | Show a data-unavailable message and do not generate weather-based advice. |

## System Users

The system has two main types of users:

1. **Farmer** – Uses the application to view weather information and receive crop advisories.
2. **Administrator** – Manages crop information and advisory rules.

## Technologies

The exact technologies used for implementation may vary depending on the implementation version. The project is designed as a web-based application with:

* Frontend
* Backend API
* Database
* External Weather API
* Rule-based Advisory Engine

## Project Documentation

The repository contains the following documentation files:

* `Requirement-Report.pdf` – Requirement analysis and project requirements.
* `SRS.pdf` – Software Requirements Specification including DFD Level 0, DFD Level 1 and Advisory Rule Table.
* `UML-Diagrams.pdf` – UML diagrams of the proposed system.

## Future Scope

The project can be extended in the future with:

* More crops and crop stages
* Region-specific advisory rules
* Weather notifications
* Multi-language support
* More detailed agricultural information
* Mobile application support
* Improved advisory rules using additional agricultural data

## Limitations

* The system depends on the availability of the external weather service.
* Weather forecasts may change and are not guaranteed.
* Advisory rules depend on the conditions configured in the system.
* The system is intended as a decision-support tool and does not replace professional agricultural advice.

## Conclusion

The Weather-Based Crop Advisory System connects weather information with crop information to provide simple and useful recommendations for farming activities. The project focuses on making weather information more meaningful for the selected crop instead of showing only general weather conditions.
