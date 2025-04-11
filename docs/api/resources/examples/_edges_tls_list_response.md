<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-11T03:22:37Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2vZ9W5SN3FGrWB8u9LfrjCy3HGR",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vZ9W5SN3FGrWB8u9LfrjCy3HGR"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2vZ9UohlMMubdr4o1p20E61sI3A",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vZ9UohlMMubdr4o1p20E61sI3A"
        },
        "enabled": true
      },
      "created_at": "2025-04-11T03:22:27Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2vZ9UreEPYfeLrOGk4tzM5f8h5Z",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vZ9UreEPYfeLrOGk4tzM5f8h5Z"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
