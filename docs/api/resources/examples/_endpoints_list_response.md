<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-29T10:07:08Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2wOmvLfUBxSIOc4vBRiOPTK7a0G",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wOmvLfUBxSIOc4vBRiOPTK7a0G"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wOmw2LDz0DCkASbvyTf5JYdhZ2",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-04-29T10:07:08Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2wOmw2LDz0DCkASbvyTf5JYdhZ2",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-29T10:07:06Z",
      "hostport": "82aa7ce67ee5.ngrok.paid:443",
      "id": "ep_2wOmviReBZIIbEA0NUc2B3Xmq2K",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2wOmtFZ37QCko4eZX5908z2wiHM",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://82aa7ce67ee5.ngrok.paid",
      "tunnel": {
        "id": "tn_2wOmviReBZIIbEA0NUc2B3Xmq2K",
        "uri": "https://api.ngrok.com/tunnels/tn_2wOmviReBZIIbEA0NUc2B3Xmq2K"
      },
      "tunnel_session": {
        "id": "ts_2wOmvmbXLKKkgxJm9XBebOrBh6z",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2wOmvmbXLKKkgxJm9XBebOrBh6z"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-29T10:07:06Z",
      "upstream_url": "http://localhost:80",
      "url": "https://82aa7ce67ee5.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-29T10:07:04Z",
      "domain": {
        "id": "rd_2wOmvLfUBxSIOc4vBRiOPTK7a0G",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2wOmvLfUBxSIOc4vBRiOPTK7a0G"
      },
      "edge": {
        "id": "edgtls_2wOmvI8W5ZLNFZf32Fnp6qfK0QM",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2wOmvI8W5ZLNFZf32Fnp6qfK0QM"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2wOmvLrDvTuiNuDA3rIzU6E8SMn",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-29T10:07:04Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
