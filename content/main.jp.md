---
weight: 10
title: API
---

# Introduction

こちらはPayPay決済を導入する開発者向けドキュメントになります。こちらのPayment SDKを使うことで簡単に開発をできるように支援することを目的としています。こちらのPayment SDKを用いてビジネス要求を実現しつつPayPayのガイドラインに合わせた実装を行うことが可能になります。

**Denne API-dokumentasjonen vart laga med  [DocuAPI](https://github.com/bep/docuapi/),  eit tema for den statiske nettstadsmakaren [Hugo](http://gohugo.io/).** 

# 認証


> To authorize, use this code:

```go
package main

import "github.com/bep/kittn/auth"

func main() {
	api := auth.Authorize("meowmeowmeow")

	// Just to make it compile
	_ = api
}
```

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
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
```

> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>
