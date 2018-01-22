# renmvars_sas
A simple macro block to rename the vars of a table in sas.

## To be used as - 
%prefixvar(work,tab1,my_,vars1);

Resultant macro variable - "mvars1"

Check by - %put |&mvars1|;
