
# Will It Run

This repo has a script `./will-it-run` which you can use to test one or more repos.
Example
```
./will-it-run https://github.com/jduimovich/single-container-app
```

The script will try to analyze the repo with a ComponentDetectionQuery and if that succeeds, create an Application and Component. 

The script will wait until a route is created.  While it waits, it will print the pods running (typically the build pods) as they progress. 

