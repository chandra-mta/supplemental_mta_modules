# supplemental_mta_modules
This repo is a set of mta supplemental modules commonly used in scripts in different areas of the codebase.
Convention is to locate these modules in a python-version-named folder on the /data/mta or /data/mta4 disks.

eg.
- /data/mta4/Script/Python3.10/MTA/
- /data/mta/Script/Python3.10/MTA/

These are typically manually included file copies inside an existing conda environment.
Note that this repo exists to compartmentalize versioning of supplemental modules for scripts.
This repo consists entirely of legacy code support and should be maintainted purely for 
versioning differences when running legacy scripts on newer python versions.
