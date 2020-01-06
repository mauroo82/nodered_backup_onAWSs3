# nodered_backup_onAWSs3
nodered_backup_onAWSs3
at any commit on NODERED, backup the flow on AWS S3

** require nodered module


node-red-contrib-s3

https://flows.nodered.org/node/node-red-contrib-s3

** in function 


msg.localFilename = "/root/.node-red/flows_debian01.json"; ## dir of file to backup
