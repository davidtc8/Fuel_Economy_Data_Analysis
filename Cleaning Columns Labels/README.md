# Cleaning Data 🧹
## What is data assessment?
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect, incomplete, irrelevant, duplicated, or improperly formatted. This data is usually not necessary or helpful when it comes to analyzing data because it may hinder the process or provide inaccurate results.
## Analysis:
Changing the data types for the following columns:
### 2008 Dataframe:
```cyl```convert float to int.

```air_pollution_score``` convert int to float.

```city_mpg, hwy_mpg, cmb_mpg``` convert string to float.

```greenhouse_gas_score``` convert from float to int.

### 2018 Dataframe:
```cyl``` extract int from string.

```air_pollution_score``` convert string to float.

```city_mpg, hwy_mpg, cmb_mpg``` convert string to float.
