# ANNOVAR_server

A webserver version of ANNOVAR. 

ANNOVAR loads DBs whenever it executes on each VCF.  Most of ANNOVAR running time comsumes for this DB loading process. 
To run ANNOVAR as server, loading DB needs to be done once at the start of web server. 

This is a code to run ANNOVAR as webserver. 
Perl's Dancer web framework was used for this process.



