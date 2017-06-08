# README

This sample Python Flask app to run on Google App Engine SE. The application
exposes an endpoint to generate random hashes for the purpose of testing an
automated test framework.

## Installation

#### AppEngine

You will need to get the google cloud SDK installed on your system. Follow the guide at https://cloud.google.com/sdk/downloads.

#### Appengine Components

```
gcloud components install app-engine-python
```

#### Lib Requirements

```
pip install -t lib -r requirements.txt
```

## Running on localhost

```
dev_appserver.py app.yaml
```

### Hosted version can be found at:

```
https://secure-random.appspot.com/
```

and example output:

```
https://secure-random.appspot.com/generate/strings?num_strings=50
```
