## Retrieve a property

> <span style="font-family:Consolas, Menlo, Monaco, \"Lucida Console\", \"Liberation Mono\", \"DejaVu Sans Mono\", \"Bitstream Vera Sans Mono\", \"Courier New\", monospace, serif"><span style="color:#a4cdfe">GET</span> /properties/:uprn</span>

```shell
$ curl 'https://your_council.metastreet.co.uk/api/v1.1/properties/10008223635' \
-H 'x-auth-api-token: 3b07c593c309ebf41330cd6f6867610eb18abe43dcf1d'
```

> EXAMPLE RESPONSE

```json
{
  "object": "property",
  "url": "/api/v1.1/properties",
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
        "addressLine4": "Dasher",
        "city": "London",
        "country": "United Kingdom",
        "county": "Greater London",
        "postcode": "A1 2BC",
        "uprn": "10008223635",
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




##### Retrieves a Property object.  Supply the Unique Property Reference Number (`uprn`) in the URL and Metastreet will return the corresponding property information.

### Parameters

<p style="max-width:440px; margin-bottom:0; margin-left:28px; padding-top:15px; padding-left:0px; border-top-style:solid; border-top-color:#eee; border-top-width:1px">
<span style="font-size:12px; color:#8792a2;">No parameters.</span>
</p>


### Returns

<p style="max-width:440px; margin-bottom:15px; margin-left:28px; border-bottom-style:solid; border-bottom-color:#eee; border-bottom-width:1px"></p>

Returns the Property object for a valid identifier.
