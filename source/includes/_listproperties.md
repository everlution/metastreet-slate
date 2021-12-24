## List all properties

> <span style="font-family:Consolas, Menlo, Monaco, \"Lucida Console\", \"Liberation Mono\", \"DejaVu Sans Mono\", \"Bitstream Vera Sans Mono\", \"Courier New\", monospace, serif"><span style="color:#a4cdfe">GET</span> /properties</span>

```shell
$ curl 'https://{your_council}.metastreet.co.uk/api/v1.1/properties' \
-H 'x-auth-api-token: 3b07c593c309ebf41330cd6f6867610eb18abe43dcf1d'
```

> EXAMPLE RESPONSE

```json
{
  "object": "property",
  "url": "/api/v1.1/properties",
  "pageSize": 100,
  "currentPage": 1,
  "totalPages": 5,
  "totalCount": 401,
  "data": [
    {
      "id": 123,
      "referenceNumbers": [
        "YCO-583484913397"
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
    ...
  ]
}
```




##### Returns a list of your properties. The properties are returned sorted by uprn, with the properties with the lowest uprn appearing first.

### Parameters

<p style="max-width:440px; margin-bottom:0; margin-left:28px; padding-top:15px; padding-left:0px; border-top-style:solid; border-top-color:#eee; border-top-width:1px">
<span style="font-size:13px; font-weight:700; color:#2a2f45; font-family:Menlo, Consolas, monospace">postcode</span> <span style="font-size:12px; font-weight:600; color:#8792a2">optional</span>
</p>

A filter on the list based on the property’s postcode field. The value must be a string.  The filter is not case-sensitive and spaces can removed.

<p style="max-width:440px; margin-bottom:0; margin-left:28px; border-bottom-style:solid; border-bottom-color:#eee; border-bottom-width:1px"></p>
