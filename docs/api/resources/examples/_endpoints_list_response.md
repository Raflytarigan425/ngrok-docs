<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-16T10:06:57Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2yaMpNBq5Ul5fg9FIU1jiUW2D2w",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yaMpNBq5Ul5fg9FIU1jiUW2D2w"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yaMpxk1f8dsLkOBNnFjai9styb",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-16T10:06:57Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2yaMpxk1f8dsLkOBNnFjai9styb",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-16T10:06:55Z",
      "hostport": "7915931bd748.ngrok.paid:443",
      "id": "ep_2yaMpippSkH5WbtLFNxvL5y0hpj",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2yaMnQ5zOHcPGe5kI5zcvNW8BLu",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://7915931bd748.ngrok.paid",
      "tunnel": {
        "id": "tn_2yaMpippSkH5WbtLFNxvL5y0hpj",
        "uri": "https://api.ngrok.com/tunnels/tn_2yaMpippSkH5WbtLFNxvL5y0hpj"
      },
      "tunnel_session": {
        "id": "ts_2yaMpolZLCndVvdloRn7FwviGPJ",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yaMpolZLCndVvdloRn7FwviGPJ"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-16T10:06:55Z",
      "upstream_url": "http://localhost:80",
      "url": "https://7915931bd748.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-16T10:06:53Z",
      "domain": {
        "id": "rd_2yaMpNBq5Ul5fg9FIU1jiUW2D2w",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yaMpNBq5Ul5fg9FIU1jiUW2D2w"
      },
      "edge": {
        "id": "edgtls_2yaMpRckPG1ih3zO4MlcBDAFZ55",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2yaMpRckPG1ih3zO4MlcBDAFZ55"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yaMpP3Dbu1emuX0ZYP0NzDR0Ax",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-16T10:06:53Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
