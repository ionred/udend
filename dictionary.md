# Data Dictionary
## immigration_fact_table

|Name|Type|Description|
|---|---|---|
|personID|DoubleType|Person Table Reference ID|
|departure_date|TimestampType|Date of Departure for Visitor|
|arrival_date|TimestampType|Date of Arrival for Visitor|
|visaTypeID|DoubleType|Visa Table Reference ID|
|portID|StringType|Port Table Reference ID|
|airlineName|StringType|Airline Code Name|
|flightNumber|StringType|Airline Flight Number|
|admissionNumber|DoubleType|Unique key for immigration entry|
|modeID|DoubleType|Mode Table Reference ID|

## port_table

|Name|Type|Description|
|---|---|---|
|portID|StringType|Primary Key Identifier|
|City|StringType|Port of Entry City|
|State|StringType|Port of Entry State|

## time_table

|Name|Type|Description|
|---|---|---|
|arrivalDate|TimestampType|Primary Key Identifier|
|year|IntegerType|Arrival Year|
|month|IntegerType|Arrival Month|
|day|IntegerType|Arrival Day|
|hour|IntegerType|Arrival Hour|
|week|IntegerType|Arrival Week|
|weekDay|IntegerType|Arrival DayofWeek (1-7 Sun-Sat)|

## mode_table

|Name|Type|Description|
|---|---|---|
|modeID|StringType|Primary Key Identifier|
|Name|StringType|Mode of Transportation for Entry|

## country_table

|Name|Type|Description|
|---|---|---|
|countryID|StringType|Primary Key Identifier|
|Name|StringType|Country of Residence|

## visa_table

|Name|Type|Description|
|---|---|---|
|visaID|StringType|Primary Key Identifier|
|Name|StringType|Visa Type/Reason for Visit|

## airport_table

|Name|Type|Description|
|---|---|---|
|airportID|StringType|Primary Key Identifier|
|name|StringType|Airport Name|
|city|StringType|Airport City|
|state|StringType|Airport State|
|iataCode|StringType|Airport IATA Code|

## person_table

|Name|Type|Description|
|---|---|---|
|personID|DoubleType|Primary Key Identifier|
|country|DoubleType|Country Table Reference ID|
|age|DoubleType|Person Age|
|gender|StringType|Person Gender|
|admissionId|DoubleType|Person Admission ID|
|occupation|StringType|Person Occupation|

</align>