# cmip6-analysis
# Master thesis Moritz Schillinger 02/2020 - 08/2020
# Topic: Impacts of Climate Change on the Amazon Rainforest: 
#        Analysis of cVeg, treefrac (biomass) and precipitation simulations from CMIP6 Earth System Models

Chapters in Code 1: All_Variable_Analysis


############################################################################################
##### 0. Packages 
############################################################################################
##### 1. Preparations
############################################################################################
##### 2. MODEL ITERATION #####
##### 2.1 cVeg SSP126
### DF der Variablen-SSP-Kombination (VSC)
##### 2.2 cVeg SSP585
### DF der Variablen-SSP-Kombination (VSC)
##### 2.3 treeFrac SSP126
### DF der Variablen-SSP-Kombination (VSC)
##### 2.4 treeFrac SSP585
### DF der Variablen-SSP-Kombination (VSC)
##### 2.5 cVeg SSP585-BGC
### DF der Variablen-SSP-Kombination (VSC)
##### 2.6 treeFrac SSP585-BGC 
### DF der Variablen-SSP-Kombination (VSC)
##### 2.8.1 cLand SSP126
### DF der Variablen-SSP-Kombination (VSC)
##### 2.8.2 cLand SSP585
### DF der Variablen-SSP-Kombination (VSC)
##### 2.9.1 GPP SSP126 
### DF der Variablen-SSP-Kombination (VSC)
##### 2.9.2 GPP SSP585
### DF der Variablen-SSP-Kombination (VSC)
##### 2.10.1 NPP SSP126
### DF der Variablen-SSP-Kombination (VSC)
##### 2.10.2 NPP SSP585
### DF der Variablen-SSP-Kombination (VSC)
##### 2.11.1 NEP SSP126
### DF der Variablen-SSP-Kombination (VSC)
##### 2.11.2 NEP SSP585
### DF der Variablen-SSP-Kombination (VSC)
##### 2.12.1 NBP SSP126
### DF der Variablen-SSP-Kombination (VSC)
##### 2.12.2 NBP SSP585
### DF der Variablen-SSP-Kombination (VSC)
#### abschange/relchange Redchnung überprüfen 
#################################
##### 3. MODEL ENSEMBLE PLOTS
####### LINE GRAPH Spmean - Altes 3.1 mit monatlichen Plots siehe 4.Papierkorb (anderes Skript)
####### 1. 1B: cVeg SSP585
####### 1. 1A: cVeg SSP126
####### 1. 1AB: cVeg SSP126 + 585
############# Plot für die neue Legende only
####### 2. 2B: treeFrac SSP585
####### 2. 2A: treeFrac SSP126
####### 2. 2AB: treeFrac SSP126 + 585
####### 3. 3: cVeg SSP585-BGC 
####### 4. 4: treeFrac SSP585-BGC
####### 5. 5A: cLand SSP126
####### 5. 5B: cLand SSP585
####### 5. 5AB: cLand SSP126 + SSP585
####### 6. 6A: gpp SSP126
####### 6. 6B: gpp SSP585
####### 6. 6AB: gpp SSP126 + 585
####### 7. 7A: npp SSP126
####### 7. 7B: npp SSP585
####### 7. 7AB: npp SSP126 + 585
####### 8. 8A: nep SSP126
####### 8. 8B: nep SSP585
####### 8. 8AB: nep SSP126 + 585 
####### 9. 9A: nbp SSP126
####### 9. 9B: nbp SSP585
####### 9. 9AB: nbp SSP126 + 585 
##### DIFFERENCE MAP B1=absolute change 
####### 1. 1A: cVeg SSP126
####### abschange 
####### relchange 
####### 1. 1B: cVeg SSP585 
####### abschange 
####### relchange 
####### 2. 2A: treeFrac SSP126
####### abschange
####### 2. 2B: treeFrac SSP585
####### absschange
####### 3. 3: cVeg SSP585-BGC 
####### abschange
####### relchange
####### 4. 4: treeFrac SSP585-BGC ######
####### abschange
####### 5. 5A: cLand SSP126 #####
####### abschange
####### relchange
####### 5. 5B: cLand SSP585
####### abschange
####### relchange 
####### 6. 6A: GPP SSP126 
####### abschange 
####### relchange 
####### 6. 6B: GPP SSP585
####### abschange
####### relchange 
####### 7. 7A: NPP SSP126
####### abschange 
####### relchange 
####### 7. 7B: NPP SSP585 #######
####### abschange
####### relchange
####### 8. 8A: NEP SSP126 #######
####### abschange
####### relchange
####### 8. 8B: NEP SSP585
####### abschange
####### relchange
####### 9. 9A: NBP SSP126
####### abschange
####### relchange 
####### 9. 9B: NBP SSP585 
####### abschange
####### relchange 
#### Percent Change Tabelle speichern 
###### THE END
####### 4. Papierkorb ######
## siehe Skript 4.Papierkorb.R ##



Chapters in Code 2: New_Diffmap

##### 0. Packages
############################################################################################
##### 1. Preparations
############################################################################################

##### DIFFMAP SINGLE MODEL ITERATION ######
###### 1A: cVeg_ssp126 
###### 1B: cVeg_ssp585
###### 2A: treeFrac_ssp126 
###### 2B: treeFrac_ssp585 
######  3: cVeg_ssp585-BGC
######  4: treeFrac_ssp585-BGC
###### 5A: cLand_ssp126
###### 5B: cLand_ssp585
###### 6A: gpp_ssp126
###### 6B: gpp_ssp585
###### 7A: npp_ssp126 
###### 7B: npp_ssp585
###### 8A: nep_ssp126
###### 8B: nep_ssp585
###### 9A: nbp_ssp126
###### 9B: nbp_ssp585 
############################################################################################
##### ENSEMBLE DIFFMAP
##### 1. 1A: cVeg SSP126 #####
####### 1530
####### 85100 
####### plot 1530+851000
####### abschange
####### relchange 
##### 1. 1B: cVeg SSP585 #####
####### 1530
####### 85100
####### plot 1530+851000 
####### abschange 
####### relchange 
##### 2. 2A: treeFrac SSP126 
####### 1530 
####### 85100
####### plot 1530+851000
####### abschange
##### 2. 2B: treeFrac SSP585 ######
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
##### 3. cVeg SSP585-BGC
####### 1530 
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 5. 5A: cLand SSP126 
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 5. 5B: cLand SSP585
####### 1530
####### 85100
####### plot 1530+851000
####### abschange 
####### relchange
##### 6. 6A: GPP SSP126
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 6. 6B: GPP SSP585
####### 1530 
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 7. 7A: NPP SSP126
####### 1530 
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 7. 7B: NPP SSP585
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 8. 8A: NEP SSP126 ######
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 8. 8B: NEP SSP585
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 9. 9A: NBP SSP126 ######
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##### 9. 9B: NBP SSP585 ######
####### 1530
####### 85100
####### plot 1530+851000
####### abschange
####### relchange
##########################################################
####### PANEL PLOTS #######
##### check out a few things
####################### LEVELPLOT #######################
##### 1A. cVeg SSP1 abschange
##### 1A. cVeg SSP1 relchange
##### 1B. cVeg SSP5 abschange
##### 1B. cVeg SSP5 relchange
##### 2A. treeFrac SSP1 abschange
##### 3. cVeg SSP5-BGC abschange
##### 3. cVeg SSP5-BGC relchange
##### 1AB. cVeg SSP1+SSP5 85100
##### 9B. NBP SSP5 85100 
##### 9A. NBP SSP1 85100
##### 8B. NEP SSP5 85100
##### 8A. NEP SSP1 85100
#########################################################
##### PANEL #############################################
#### PRECIPITATION DIFFMAP
### Stack abschange ssp1+5
### Stack relchange ssp1+5
