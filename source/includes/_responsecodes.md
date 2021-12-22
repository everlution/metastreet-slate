# Response codes

> EXAMPLE ERROR MESSAGE

```json
http code 404
{
  "error": "Invalid endpoint"
}
```

Metastreet uses conventional HTTP response codes to indicate the success or failure of an API request. In general: Codes in the 2xx range indicate success. Codes in the 4xx range indicate an error that failed given the information provided (e.g., a required parameter was omitted, a charge failed, etc.). Codes in the 5xx range indicate an error with Metastreet's servers (these are rare).

Response Code | Meaning
---------- | -------
200 | OK -- Everything worked as expected
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API key is wrong.
402 | Request failed -- The parameters were valid but the request failed.
403 | Forbidden -- The API key doesn't have permissions to perform the request.
404 | Not Found -- The requested resource doesn't exist.
405 | Method Not Allowed -- You tried to access a resource with an invalid method.
406 | Not Acceptable -- You requested a format that isn't available.
410 | Gone -- The resource requested has been removed from our servers.
429 | Too Many Requests -- Too many requests hit the API too quickly. We recommend an exponential backoff of your requests.
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
