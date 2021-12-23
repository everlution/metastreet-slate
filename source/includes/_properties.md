# Properties

> EXAMPLE REQUEST

```shell
  $ curl 'https://example-council.metastreet.co.uk/api/v1.1/properties?key={your_api_key}'
```

> EXAMPLE RESPONSE

```json
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

#### Provides top level property data including address, UPRN, USRN and case reference numbers of any licence applications.

More stuff here.
