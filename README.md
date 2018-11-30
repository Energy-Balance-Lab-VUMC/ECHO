# ECHO
Codebase for Actimetry Core in the Glucagon-Like Peptide-1 Agonist Effects on Energy Balance in Hypothalamic Obesity (ECHO) study.
  
  
## Guidelines
  
* Wear Detection
  * use 15 second level files to detect wear status
* Sleep Detection
  * aggregate to 60 second level and then run sleep algorithm
  * map the results back to 15 second level data
* Physical Activity
  * use 15 second level files to mark activity levels
  
## File Structure
```
| /scripts/
   | process_data.R
   | graphs.R
   | table.R
   | statistical_analysis.R
```
  
## R Packages
* PhysicalActivity 0.2-2
* PhysActBedRest 1.0
* RSQLite 2.1.1
* ggplot2 3.1.0
