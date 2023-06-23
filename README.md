# CrowdScript
Allows execution of a CrowdStike script or command on multiple hosts.

This will execute any PS, bash, or CS builtin commands on the hosts specified in the "ComputersList.txt".

The results of those commands, if any, should be written to the "Results.txt" file. 

The main focus is on the Base command and Main command. If you need to use the built in commands, the base command and main command are the same. For exmaple: Base Command:ps Main Command:ps

When using a PS or bash script, save it in CS first and replace:
-CloudFile="MyScript"
the base command for scripts saved in CS is: runscript
