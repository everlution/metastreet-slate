# Pagination

> EXAMPLE REQUEST

```shell
  $ curl 'https://your-council.metastreet.co.uk/api/v1.1/properties?key={your_api_key}'
```

> EXAMPLE RESPONSE

```json
"object": "property",
"url": "https://your-council.metastreet.co.uk/api/v1/properties",
"pageSize": 100,
"currentPage": 1,
"totalPages": 3,
"totalCount": 40,
"data": [
  {
    "id": 123,
    "referenceNumbers": [
      "string"
    ],
    "address": {
      "addressLine1": "4, Dasher Place",
      "addressLine2": "Dasher Street",
      "addressLine3": "Dasher Estate",
      "addressLine4": "Dasher",
      "city": "London",
      "country": "United Kingdom",
      "county": "Greater London",
      "postcode": "A1 2BC",
      "uprn": "12345678910",
      "usrn": "1234567",
      "latitude": "1.230045",
      "longitude": "-5.430021",
      "ward": "Dasher Ward"
    }
  }
]
```

All top-level API resources have support for pagination.

The `pageSize` and `page` query parameters let you control pagination.

Using the `pageSize` parameter, you can define the number of items to be displayed on one page.  By default, 100 results are returned per page and only one page is returned per request.

Using the `page` parameter you can select which page you would like to be returned.

To set the `pageSize` and `page` parameters, you should pass a value greater than `0` as a query argument.
