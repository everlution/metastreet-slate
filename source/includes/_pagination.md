# Pagination

> EXAMPLE REQUEST

```shell
  $ curl 'https://example-council.metastreet.co.uk/api/v1.1/properties?key={your_api_key}'
```

> EXAMPLE RESPONSE

```shell
"object": "property",
"url": "https://example-council.metastreet.co.uk/api/v1/properties",
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
      "addressLine1": "Flat 123",
      "addressLine2": "Imaginary Court",
      "addressLine3": "Example Estate",
      "addressLine4": "Abstract City",
      "city": "London",
      "country": "United Kingdom",
      "county": "Fantasy",
      "postcode": "A1 2BC",
      "uprn": "12345678910",
      "usrn": "1234567",
      "latitude": "1.230045",
      "longitude": "-5.430021",
      "ward": "Dream Ward"
    }
  }
]
```

All top-level API resources have support for pagination.

The `pageSize` and `page` query parameters let you control pagination.

Using the `pageSize` parameter, you can define the number of items to be displayed on one page.  By default, 100 results are returned per page and only one page is returned per request.

Using the `page` parameter you can select which page you would like to be returned.

To set the `pageSize` and `page` parameters, you should pass a value greater than `0` as a query argument.
