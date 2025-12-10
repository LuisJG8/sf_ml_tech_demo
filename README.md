# Setup Guide ⚙️


## Step 1

Login to your Snowflake account ❄️


## Step 2

Go to SQL Workspaces (under the Projects section) and run the setup.sql file (click on the v next to the ▶️) and then click on "Run all"


## Step 3

Go to the stage BOATS_STAGE. 

Stage location: Horizon Catalog > Catalog > SNOW_ML_DB > SNOW_ML_SCHEMA > STAGES > BOATS_STAGE 

On the top right, click on + Files, then click on Browse

Upload all files in the boats_pdf_extracted_data folder


## Step 4

Go to Notebooks (under the Projects section), on the top right click the v symbol (right besides the + Notebook button)

**Notebook Settings:**

- Notebook Location = SNOW_ML_DB, SNOW_ML_SCHEMA  
- Runtime = Run on Container  
- Runtime Version = Snowflake ML Runtime CPU 1.0  
- Compute Pool = SYSTEM_COMPUTE_POOL_CPU  
- Query Warehouse = SNOW_ML_PIPELINE  

Once the notebook is open, click on the + sign and upload the following:
<img width="666" height="352" alt="image" src="https://github.com/user-attachments/assets/2965c455-19af-43ca-a988-13c96a7773d5" />


**CSV Files:**

- boat_data_.csv
- catamaran_extracted_data.csv
- monohull_extracted_data.csv
- power_catamaran_extracted_data.csv

## Step 5

Happy Coding! 😄
