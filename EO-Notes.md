## To deploy the whole thing: 
sls deploy

## To deploy an update of the function:
sls deploy function --function hello

## To invoke it locally:
sls invoke local --function hello --path event.json

## Log info? 
sls invoke --function hello --log

