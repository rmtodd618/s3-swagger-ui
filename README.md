This repo is for setting up a s3 bucket to display your swagger documents.
1) Create your s3 bucket in aws.
2) Under Permissions-Access Control List-Public access-Everyone- Select List objects
3) Under Permissions-Bucket policy- Copy and paste the configs/BucketPolicy into the area and save it
4) Under Permissions-CORS configuration- Copy and paste the configs/CORS configuration into the area and save it
5) do a git pull of this repo
6) put you swagger doc along side everything in this repo
7) edit the index.html file on line 77 to represent your public bucket name url/name of your json
8) upload all of your docs into the s3 bucket.
9) You should now see the swagger page

If you are using a dns name with cloud front. Be sure to change the index.html file to your dns name or it will not work.
