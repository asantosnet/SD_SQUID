# SD_SQUID

This code study the fixed points and their stability for a DC_SQUID. To know more on how the system was modeled and the results check the report. 

Numerical Calculation also studied the time evolution of the system
by solving the differential equations characterizing the latter. This was done using scypy.ode function in python. 

There is a bug on the Analytique_DCSQUID_vf when calculating the fixed points given by the system of equations 9 ( see report) This is likely due to how the periodicity of arccos(i/2cos(x)^x) was considered. 


