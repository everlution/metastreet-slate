# Authentication

> EXAMPLE AUTHENTICATED REQUEST

```shell
$ curl 'https://{your_council}.metastreet.co.uk/api/v1.1/properties' \
-H 'x-auth-api-token: 3b07c593c309ebf41330cd6f6867610eb18abe43dcf1d'
```

> EXAMPLE RESPONSE

```json
{
  "object": "property",
  "url": "/api/v1.1/properties",
  ...
  "data": [ {
    "id": 1248152,
    "referenceNumbers": [
      "YCO-583484913397"
    ],
    "address": {
      "addressLine1": "4, Dasher Place",
      "addressLine2": "Dasher Street",
      "addressLine3": "Dasher Estate",
      ...
    }
    ...
  },
  ]
}
```

The Metastreet API uses API keys to authenticate requests. You can view your API key(s) in `Settings -> Integrations` section of the council backend.  If you can't find your API key(s), please contact your account manager.

Your API keys carry many privileges, so be sure to keep them secure! Do not share your secret API keys in publicly accessible areas such as GitHub, client-side code, and so forth.

All requests to our API must include your API key in the `x-auth-api-token` header.

All API requests must be made over HTTPS. Calls made over plain HTTP will fail. API requests without authentication will also fail.
