# ahkverifierdatabase
This is a simple database to store data for my AHK projects such as login data
All login data are safely hashed with salt. Your data is kept safe and you may request a data reset or data wipe whenever.

# The files
## HWIDS
This file contains the login details with proper cryptography for the algorithm to fetch from. 
This is manually updated for now, will be automatized later on.
Reminder that this solution is because i can't be asked to setup a whole homeserver and SQL database for this, and i lack the funds to rent a server. 
But at least we have transparency, i guess?
## Modules
This file contains the names of the currently verified and registered modules for the module fetcher.
The script will only recognize modules that are stored in the database.
## Versionid
This file contains a single string that identifies the latest version. This is used when verifying integrity and ensuring up-to-date versions in 1.2.2 and newer releases.
