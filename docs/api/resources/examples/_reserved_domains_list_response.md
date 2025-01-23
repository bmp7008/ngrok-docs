<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-01-23T10:07:45Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3rr5ss3xknkepb75v.local-ngrok-cname.com",
			"created_at": "2025-01-23T10:07:45Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2s1d9qD2vXl7djmrKnYl46ci1LI",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2s1d9qD2vXl7djmrKnYl46ci1LI"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2s1d9qfhxJlZv8HBBYZkxEX0Lhb",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2s1d9qfhxJlZv8HBBYZkxEX0Lhb"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3rr5ss3xknkepb75v.local-ngrok-cname.com",
			"created_at": "2025-01-23T10:07:45Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2s1d9mh5Th7xfunIn4uwpRFV5fd",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2s1d9mh5Th7xfunIn4uwpRFV5fd"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
