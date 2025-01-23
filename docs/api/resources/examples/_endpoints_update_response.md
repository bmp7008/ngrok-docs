<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"bindings": ["public"],
	"created_at": "2025-01-23T10:08:06Z",
	"description": "Sample Cloud Endpoint",
	"domain": {
		"id": "rd_2s1dBmpWrNgtRkA8k2nrWKzO5gS",
		"uri": "https://api.ngrok.com/reserved_domains/rd_2s1dBmpWrNgtRkA8k2nrWKzO5gS"
	},
	"hostport": "endpoint-example2.com:443",
	"id": "ep_2s1dCNeBtkF6tJXDIlOkUVXJYVU",
	"metadata": "{\"environment\": \"staging\"}",
	"pooling_enabled": false,
	"proto": "https",
	"public_url": "https://endpoint-example2.com",
	"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
	"type": "cloud",
	"updated_at": "2025-01-23T10:08:06Z",
	"uri": "https://api.ngrok.com/endpoints/ep_2s1dCNeBtkF6tJXDIlOkUVXJYVU",
	"url": "https://endpoint-example2.com"
}
```
