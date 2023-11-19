# Project to do analysis on Sales Record

### Project Motivation
 - I downloaded Sales File CSV From this location - https://catalog.data.gov/dataset/warehouse-and-retail-sales
 - I will perform analysis using SQL on this data

### Steps
 1. Imported CSV into database into table 
 ```
CREATE TABLE public.warehouse_retail_sale (
	"YEAR" int4 NULL,
	"MONTH" int4 NULL,
	"SUPPLIER" text NULL,
	"ITEM_CODE" text NULL,
	"ITEM_DESCRIPTION" text NULL,
	"ITEM_TYPE" text NULL,
	"RETAIL_SALES" text NULL,
	"RETAIL_TRANSFERS" text NULL,
	"WAREHOUSE_SALES" text NULL
); 
```