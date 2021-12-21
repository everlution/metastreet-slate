# Authentication

The Metastreet API uses API keys to authenticate requests. You can view your API key(s) in `Settings -> Integrations` section of the council backend.  If you can't find your API key(s), please contact your account manager.

<aside class="warning">
Your API keys carry many privileges, so be sure to keep them secure! Do not share your secret API keys in publicly accessible areas such as GitHub, client-side code, and so forth.
</aside>

The API key needs to be included in the URL of each end-point as a query parameter even for POST requests.

All API requests must be made over HTTPS. Calls made over plain HTTP will fail. API requests without authentication will also fail.


> TESTTo authorize, use this code:

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here" \
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
```
