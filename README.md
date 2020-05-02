# google cloud platform note


## basic setting
```bash
# initialize bash account setting 
gcloud init

gcloud info

gcloud components list
```

## sourcecode repo

```bash
#check source repo 
gcloud source repos list
```

## deploy app to App Engine
``` bash
# check app status
gcloud app services list
gcloud app instances list
gcloud app versions list

# deploy code to app
gcloud app deploy app.yaml
```

