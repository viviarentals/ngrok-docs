<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-29T10:07:13Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2wOmwYo89kA6jBYVdWHHVd5tOi8",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wOmwYo89kA6jBYVdWHHVd5tOi8"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2wOmvOzm0wUBu1YYxeYjm8tUsok",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2wOmvOzm0wUBu1YYxeYjm8tUsok"
        },
        "enabled": true
      },
      "created_at": "2025-04-29T10:07:03Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2wOmvI8W5ZLNFZf32Fnp6qfK0QM",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2wOmvI8W5ZLNFZf32Fnp6qfK0QM"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
