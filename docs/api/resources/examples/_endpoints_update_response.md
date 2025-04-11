<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-11T04:36:14Z",
  "description": "Sample Cloud Endpoint",
  "domain": {
    "id": "rd_2vZISVbclrQL67uLXHZYEYQbffZ",
    "uri": "https://api.ngrok.com/reserved_domains/rd_2vZISVbclrQL67uLXHZYEYQbffZ"
  },
  "hostport": "endpoint-example2.com:443",
  "id": "ep_2vZITAagEhP7w8gVXU1hn9nlgTz",
  "metadata": "{\"environment\": \"staging\"}",
  "pooling_enabled": false,
  "proto": "https",
  "public_url": "https://endpoint-example2.com",
  "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
  "type": "cloud",
  "updated_at": "2025-04-11T04:36:14Z",
  "uri": "https://api.ngrok.com/endpoints/ep_2vZITAagEhP7w8gVXU1hn9nlgTz",
  "url": "https://endpoint-example2.com"
}
