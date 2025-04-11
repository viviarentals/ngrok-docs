<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-11T03:22:32Z",
  "description": "sample cloud endpoint",
  "domain": {
    "id": "rd_2vZ9Uq7gVZ8H5pZoqUgudVrFKRz",
    "uri": "https://api.ngrok.com/reserved_domains/rd_2vZ9Uq7gVZ8H5pZoqUgudVrFKRz"
  },
  "hostport": "endpoint-example2.com:443",
  "id": "ep_2vZ9VS9L6Z0OQbtobjeu12oXVam",
  "metadata": "{\"environment\": \"staging\"}",
  "pooling_enabled": false,
  "proto": "https",
  "public_url": "https://endpoint-example2.com",
  "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
  "type": "cloud",
  "updated_at": "2025-04-11T03:22:32Z",
  "uri": "https://api.ngrok.com/endpoints/ep_2vZ9VS9L6Z0OQbtobjeu12oXVam",
  "url": "https://endpoint-example2.com"
}
