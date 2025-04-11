<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
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
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-11T03:22:30Z",
      "hostport": "e9f54d336057.ngrok.paid:443",
      "id": "ep_2vZ9VDVRF3ry8WgpFYo2M5RMcFW",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2vZ9Sgl0khUdy9Iz1CtqwJfLRQZ",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://e9f54d336057.ngrok.paid",
      "tunnel": {
        "id": "tn_2vZ9VDVRF3ry8WgpFYo2M5RMcFW",
        "uri": "https://api.ngrok.com/tunnels/tn_2vZ9VDVRF3ry8WgpFYo2M5RMcFW"
      },
      "tunnel_session": {
        "id": "ts_2vZ9VHD4uWdK5KWkwQo4wwct9N9",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2vZ9VHD4uWdK5KWkwQo4wwct9N9"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-11T03:22:30Z",
      "upstream_url": "http://localhost:80",
      "url": "https://e9f54d336057.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-11T03:22:28Z",
      "domain": {
        "id": "rd_2vZ9Uq7gVZ8H5pZoqUgudVrFKRz",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vZ9Uq7gVZ8H5pZoqUgudVrFKRz"
      },
      "edge": {
        "id": "edgtls_2vZ9UreEPYfeLrOGk4tzM5f8h5Z",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2vZ9UreEPYfeLrOGk4tzM5f8h5Z"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vZ9UvaNG3pKKPSfj4VFsw9K2EV",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-11T03:22:28Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
