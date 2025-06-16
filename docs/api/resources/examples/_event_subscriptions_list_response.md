<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-06-16T10:06:59Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2yaMqG7NxPt423nkZWyGWaihccw",
          "uri": "https://api.ngrok.com/event_destinations/ed_2yaMqG7NxPt423nkZWyGWaihccw"
        }
      ],
      "id": "esb_2yaMqJh7Niq3SppArk9nd8lLoWa",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2yaMqJh7Niq3SppArk9nd8lLoWa/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2yaMqJh7Niq3SppArk9nd8lLoWa"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
