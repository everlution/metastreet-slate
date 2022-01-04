# Pagination

> EXAMPLE PAGINATION REQUEST

```shell
$ curl 'https://your_council.metastreet.co.uk/api/v1.1/properties?pageSize=50&page=4' \
-H 'x-auth-api-token: 3b07c593c309ebf41330cd6f6867610eb18abe43dcf1d'
```

> EXAMPLE RESPONSE

```json
{
  "object": "property",
  "url": "https://your-council.metastreet.co.uk/api/v1/properties",
  "pageSize": 50,
  "currentPage": 4,
  "totalPages": 9,
  "totalCount": 401,
  "data": [
    {
      "id": 1248196,
      "referenceNumbers": [
        "YCO-583484913397"
      ],
      "address": {
        "addressLine1": "4 Dasher Place",
        "addressLine2": "Dasher Street",
        "addressLine3": "Dasher Estate",
        ...
      }
    }
    ...
  ]
}
```

All top-level API resources have support for pagination.

The `pageSize` and `page` query parameters let you control pagination.

One page is returned per request.  Using the `pageSize` parameter, you can define the number of items to be displayed on this page - the default is 100 items.

Using the `page` parameter you can select which page you would like to be returned.

To set the `pageSize` and `page` parameters, you should pass a value greater than `0` as a query argument.
