i alayze the e vehicle sales data and creating a actionable insights with tableau 

calculated fields are:
1.total vehicles = countd([vehicle id])
2.average vehicle range = avg([vehicle id])
3.total BEV vehicle = countd( if [electric vehicle type] = 'BEV' then [vehicle id] end 
4.total PHEV vehicle = countd( if [electric vehicle type] = 'PHEV' then [vehicle id] end 

creating parameter by finding top N 
 
