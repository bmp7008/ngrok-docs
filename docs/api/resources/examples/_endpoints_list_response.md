<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-01-23T10:08:06Z",
			"description": "sample cloud endpoint",
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
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-23T10:08:04Z",
			"hostport": "278fe57b5e14.ngrok.paid:443",
			"id": "ep_2s1dCEJPwlZQt65RWhcGzYvAcFT",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2s1d9ecm7TEXvopWGUxAKZH753Y",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://278fe57b5e14.ngrok.paid",
			"tunnel": {
				"id": "tn_2s1dCEJPwlZQt65RWhcGzYvAcFT",
				"uri": "https://api.ngrok.com/tunnels/tn_2s1dCEJPwlZQt65RWhcGzYvAcFT"
			},
			"tunnel_session": {
				"id": "ts_2s1dC9rKDBjFrfMPY9fWag4ks1S",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2s1dC9rKDBjFrfMPY9fWag4ks1S"
			},
			"type": "ephemeral",
			"updated_at": "2025-01-23T10:08:04Z",
			"upstream_url": "http://localhost:80",
			"url": "https://278fe57b5e14.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-23T10:08:02Z",
			"domain": {
				"id": "rd_2s1dBmpWrNgtRkA8k2nrWKzO5gS",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2s1dBmpWrNgtRkA8k2nrWKzO5gS"
			},
			"edge": {
				"id": "edgtls_2s1dBqu7TyATu4iSsWfmGku55Uz",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2s1dBqu7TyATu4iSsWfmGku55Uz"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2s1dBqRg1lp6OWFGAUL9QOE08Bx",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-01-23T10:08:02Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
