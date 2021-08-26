# nami-google-token-validator

A simple Python 3 CLI for validating a Google Play Purchase Token via the Google Developer API.

### Purchase token is for a subscription purchase


```
./google_token_validator.py  /path/to/base64_encoded_receipt
```

### Purchase token is for a onetime purchase

This is necessary to receive a purchase response for a purchase tokens representing a one time purchase


```
./google_token_validator.py  /path/to/base64_encoded_receipt -s your_app_shared_secret
```

### Don't print responseBody to console

```
./google_token_validator.py  /path/to/base64_encoded_receipt --quiet
```
