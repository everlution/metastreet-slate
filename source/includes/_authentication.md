# Authentication

> AUTHENTICATED REQUEST

```
$ curl 'https://api.ma-monitor.co.uk/v1/search?key={your_api_key}'
-d '{"tradingCompany": "PLC"}'
```

The Metastreet API uses API keys to authenticate requests. You can view your API key(s) in `Settings -> Integrations` section of the council backend.  If you can't find your API key(s), please contact your account manager.

Your API keys carry many privileges, so be sure to keep them secure! Do not share your secret API keys in publicly accessible areas such as GitHub, client-side code, and so forth.

The API key needs to be included in the URL of each end-point as a query parameter even for POST requests.

All API requests must be made over HTTPS. Calls made over plain HTTP will fail. API requests without authentication will also fail.
