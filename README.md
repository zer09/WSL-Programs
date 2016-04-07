# WSL-Programs
A community powered list of programs that work (and those that don't) on the Windows subsystem for Linux

Please feel free to contribute programs you have tested to the table below. If you need help with the markdown, please review [a primer](https://help.gamejolt.com/markdown)

#The list:

Program Name  | apt name if different (blank otherwise) | Functionality rating (0-5) | website if not on apt | Notes
------------- | --------------------------------------- | -------------------------- | --------------------- | ------------------
xorg | | 4 | | Requires Configuration and an X server on Windows
nano | | 3 | | Functions correctly, but does not display correctly
ip | | 0 |  | Unable to Access Network Interfaces (Should be localhost for all connections)
ifconfig | | 0 | | Unable to Access Network Interfaces (Should be localhost for all connections)
iwconfig | | 0 | | Unable to Access Network Interfaces (Should be localhost for all connections)
Apache server | apache2 | 2 | | Must use a loopback for networking, buggy
gcc | build-essential | 4 | | more testing needed
mtr | | 0 | | doesn't run
docker | | 0 | | doesn't run
npm | | 4 | | some packages fail due to permissions
ssh | | 4 | | ssh -i works


