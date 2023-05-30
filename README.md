# SNMP
I have written a script to probe an SNMP agent and calculate the rate of change for multiple OIDs between successive probes or samples. 
This script can handle both 32-bit and 64-bit counter types and address counter wraps.  
The specific parameters are agent details, sample frequency, number of samples and OIDs to be probed. 
The output displays the sample time, followed by the rate of change for each OID.

