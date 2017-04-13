# py-gcp-appengine-noop

a simple do-nothing application that runs on google standard app engine.

deploying services to a google project mandates that a 'default' application must exists.
this application provides a basic do-nothing application that can be deployed as this 'default'.


## deploy to gcp

```bash
gcloud app deploy ./app.yaml
```
