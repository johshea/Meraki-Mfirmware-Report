# Meraki-Mfirmware-Report
Collect current firmware state, by Network or ORG wide

#this script is a prototype, and very specific. As always it should be executed on aproduction env only after thourough testing.
#This script functions as a way to validate an org or networks current firmware state.
#the dashboard
##########################################################
# Prep
#pip3 install requests
#pip3 install  pandas
##########################################################
#
# -k <your api key> [MANDATORY]
# -o <your org name> [MANDATORY]
# -n <specific network name> [optional (not case sensitive)]
#
# usage python3 main.py -k <api key> -o <specific org name> -n <network name>
######################################################################################################
