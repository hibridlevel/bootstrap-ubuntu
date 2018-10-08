# Ubuntu Bootstrap
Bash script to automate the configuration and package installation for Ubuntu systems.

## Install ubuntu-bootstrap
Run the following command on the Ubuntu box you wish to setup:  
`bash <(curl -L https://git.hibridlevel.hu/kubernetes/ubuntu-bootstrap/raw/master/bootstrap.sh)`

## Modules
Please manually review each modules source to make sure you want to perform all of the actions.
If you do not want a specific module to run, just comment out the `source core/<module>.sh` line inside `bootstrap.sh`.

### system.sh
Set IP address install Basic packages 

### kubernetes.sh
Bootstrap settings for kubernetes cluster (disable swap)

## Disclaimer
By using these scripts you acknowledge that the author is not responsible for any misconfigurations, damages, data loss, or other problems that may be caused by the use of these scripts. 
