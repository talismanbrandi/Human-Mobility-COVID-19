For the SafeGraph mobility Datasets:  
```
aws s3 sync s3://sg-c19-response/monthly-patterns/patterns_backfill/2020/05/07/12/<year>/<month> <year>/<month> --profile safegraphws --endpoint https://s3.wasabisys.com
```

Get the Place ID to CBG file and unzip it in this directory ('datasets'):  
https://drive.google.com/file/d/14J5jj-oiPMYzPqbCxJ2Jy0tLV3fb8M6F/view