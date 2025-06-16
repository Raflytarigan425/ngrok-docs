<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-16T10:07:03Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2yaMqjAu8SczBOzdDrO2j1bBJwd",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yaMqjAu8SczBOzdDrO2j1bBJwd"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2yaMpKXiX9ww3euc7K9MzgaNhPn",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2yaMpKXiX9ww3euc7K9MzgaNhPn"
        },
        "enabled": true
      },
      "created_at": "2025-06-16T10:06:52Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2yaMpRckPG1ih3zO4MlcBDAFZ55",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yaMpRckPG1ih3zO4MlcBDAFZ55"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
