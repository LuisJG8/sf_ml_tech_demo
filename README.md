# Setup Guide ⚙️


## Step 1

Login to your Snowflake account ❄️


## Step 2

Go to SQL Workspaces (under the Projects section) and run the setup.sql file (click on the v next to the ▶️) and then click on "Run all"


## Step 3

Go to the stage called BOATS_STAGE. 

Stage location: Horizon Catalog > Catalog > SNOW_ML_DB > SNOW_ML_SCHEMA > STAGES > BOATS_STAGE 

On the top right of the screen click on + Files

Upload all files in the boats_pdf_extracted_data folder

## Step 4

Go to Snowflake Notebooks, on the top right click of the screen, click the v sign (right besides the + Notebook button)


## Step 5

**Notebook Settings:**

- Notebook Location = SNOW_ML_DB, SNOW_ML_SCHEMA  
- Runtime = Run on Container  
- Runtime Version = Snowflake ML Runtime GPU 1.0  
- Compute Pool = SYSTEM_COMPUTE_POOL_CPU  
- Query Warehouse = SNOW_ML_PIPELINE  



## Step 6

Happy Coding! 😄
