# cloud7


# Take Backup for Running deployment 
  step 1: kubectl get deploy | awk 'NR>1 {print $1} ' > deploymentname.txt <br>
  step 2: run the script (running-script.sh) with command: sh running-script.sh <br>
