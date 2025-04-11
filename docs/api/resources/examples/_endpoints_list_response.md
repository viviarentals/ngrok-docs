<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-11T04:36:14Z",
      "description": "sample cloud endpoint",
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
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-11T04:36:12Z",
      "hostport": "f8840bf32bfe.ngrok.paid:443",
      "id": "ep_2vZISwYd0LkdMG5mgiiivYLwy3Y",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2vZIQYg0ukOqDGcZkWbdOFhIVz4",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://f8840bf32bfe.ngrok.paid",
      "tunnel": {
        "id": "tn_2vZISwYd0LkdMG5mgiiivYLwy3Y",
        "uri": "https://api.ngrok.com/tunnels/tn_2vZISwYd0LkdMG5mgiiivYLwy3Y"
      },
      "tunnel_session": {
        "id": "ts_2vZIStE9DkYZuyqLdLpZUz3e5RM",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2vZIStE9DkYZuyqLdLpZUz3e5RM"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-11T04:36:12Z",
      "upstream_url": "http://localhost:80",
      "url": "https://f8840bf32bfe.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-11T04:36:10Z",
      "domain": {
        "id": "rd_2vZISVbclrQL67uLXHZYEYQbffZ",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vZISVbclrQL67uLXHZYEYQbffZ"
      },
      "edge": {
        "id": "edgtls_2vZIScx3lCGKyLI3HpCvsNw6CB0",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2vZIScx3lCGKyLI3HpCvsNw6CB0"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vZISb8RTMDZaZ00y6Y92aloOiT",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-11T04:36:10Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
