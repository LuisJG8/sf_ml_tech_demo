Step 1

Loging to your Snowflake account

Step 2

Run the setup.sql file in SQL Workspaces

Step 3

Upload all the pdf files from the boats_pdf_extracted_data folder, to the stage called BOATS_STAGE

Step 4 

Go to Snowflake Notebooks, on the top right click of the screen, click the v sign (right besides the + Notebook button)

Step 5

For Runtime select "Run on Container", for Runtime Version select "Snowflake ML Runtime GPU 1.0", for Compute pool select "SYSTEM_COMPUTE_POOL_CPU", for Query Warehouse select SNOW_ML_PIPELINE
