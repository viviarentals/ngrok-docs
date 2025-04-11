<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-11T04:36:19Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2vZITp1TA4nDgJSuISwQ3Xjchy3",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vZITp1TA4nDgJSuISwQ3Xjchy3"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2vZISYDDzqB1sVthPbE8qX0Ujlb",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vZISYDDzqB1sVthPbE8qX0Ujlb"
        },
        "enabled": true
      },
      "created_at": "2025-04-11T04:36:09Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2vZIScx3lCGKyLI3HpCvsNw6CB0",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vZIScx3lCGKyLI3HpCvsNw6CB0"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
