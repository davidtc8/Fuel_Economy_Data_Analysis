# Fixing Data Types 🔨
## Importance of Data Types
When doing data analysis, it is important to make sure you are using the correct data types; otherwise you may get unexpected results or errors.
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

## Why changing the dataframe:
Before we do any **analysis**, we need to clean the datatypes, so we can start to the phase of analysis through matplotlib. 