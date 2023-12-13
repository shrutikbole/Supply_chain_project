# Supply_chain_project

### Intro - Business Problem Statement :
An FMCG company entered into the instant noodles business two years back. Their higher management has noticed that there is a miss match in the demand and supply. Where the demand is high, supply is pretty low and where the demand is low, supply is pretty high. In both ways, it is an inventory cost loss to the company; hence, the higher management wants to optimize the supply quantity in every warehouse in the entire country.

### Goal & Objective:
This exercise aims to build a model, using historical data that will determine the optimum weight of the product to be shipped each time to the warehouse.
Also, try to analyze the demand pattern in different pockets of the country so management can drive the advertisement campaign, particularly in those pockets.
This is the first phase of the agreement; hence, the company has shared very limited information. Once you are able to showcase a tangible impact with this much information then the company will open the
360-degree data lake for your consulting company to build a more robust model.
Data Dictionary" or "Key Fields Description :
Here is a summary of the key fields in the dataset:

### Field Name	Description
Warehouse_id:	Unique identifier for each product warehouse.
WH_Manager_ID:	Employee ID of the warehouse manager.
Location_type:	Categorization of warehouse location (city or village).
WH_capacity_size:	Storage capacity of the warehouse.
Zone:	Geographical zone of the warehouse.
WH_regional_zone:	Regional zone of the warehouse under each zone.
num_refill_req_l3m:	Number of times refilling requested in the last 3 months.
transport_issue_l1y:	Indicator of any transport issues reported in the last year.
Competitor_in_mkt:	Number of instant noodles competitors in the market.
retail_shop_num:	Number of retail shops selling the product under the warehouse area.
wh_owner_typ:e	Ownership type of the warehouse (company-owned or rented).
distributor_num:	Number of distributors working between the warehouse and retail shops.
flood_impacted:	Indicator if the warehouse is located in a flood-impacted area.
Flood_proof:	Indicator if the warehouse is flood-proof.
electric_supply:	Indicator if the warehouse has electric backup (generator) for load shedding.
dist_from_hub:	Distance between the warehouse and the production hub (in kms).
workers_num:	Number of workers in the warehouse.
wh_est_year:	Year of warehouse establishment.
storage_issue_reported_l3m:	Indicator of any storage issues reported in the last 3 months.
temp_reg_mach:	Indicator whether the warehouse has temperature regulating machines.
approved_wh_govt_certificate:	Type of government certificate issued to the warehouse.
wh_breakdown_l3m:	Number of times the warehouse faced a breakdown in the last 3 months.
govt_check_l3m	Number of times government officers visited the warehouse to check stored food quality.
product_wg_ton (Target_column):	Weight of the product (in tons) shipped in the last 3 months.

This data dictionary provides essential information about each field in the dataset, helping you understand the dataset's structure and the role of each variable in the analysis.
