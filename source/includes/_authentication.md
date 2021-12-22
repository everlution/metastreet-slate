# Authentication

> AUTHENTICATED REQUEST

```shell
  $ curl 'https://example-council.metastreet.co.uk/api/v1.1/properties?key={your_api_key}'
```


> EXAMPLE RESPONSE

```json
	{
    "id": 1,
    "title": "Dubnobasswithmyheadman",
    "artist": "Underworld",
    "year": 1994
  }
  {
    "id": 2,
    "title": "ISDN",
    "artist": "Future Sound of London",
    "year": 1994
  }
```

The Metastreet API uses API keys to authenticate requests. You can view your API key(s) in `Settings -> Integrations` section of the council backend.  If you can't find your API key(s), please contact your account manager.

Your API keys carry many privileges, so be sure to keep them secure! Do not share your secret API keys in publicly accessible areas such as GitHub, client-side code, and so forth.

The API key needs to be included in the URL of each end-point as a query parameter even for POST requests.

All API requests must be made over HTTPS. Calls made over plain HTTP will fail. API requests without authentication will also fail.
