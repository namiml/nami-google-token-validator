# nami-google-token-validator

A simple Python 3 CLI for validating a Google Play Purchase Token via the Google Developer API.


To install the Google Developer APIs for Python:

```
pip install google-api-python-client
```

### Purchase token is for a subscription purchase


```
./google_token_validator.py /path/to/google_service_credentials.json [package_name] [product_id] [purchase_token]
```

### Purchase token is for a onetime purchase


```
./google_token_validator.py /path/to/google_service_credentials.json [package_name] [product_id] [purchase_token] --onetime
```

### Don't print response to console

```
./google_token_validator.py /path/to/google_service_credentials.json [package_name] [product_id] [purchase_token] --quiet
```
