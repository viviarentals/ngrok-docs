<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-04-29T10:07:09Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2wOmw50WOZyTjdzWH02rTA1rsZL",
          "uri": "https://api.ngrok.com/event_destinations/ed_2wOmw50WOZyTjdzWH02rTA1rsZL"
        }
      ],
      "id": "esb_2wOmw7inuyOSURsfyQcwLjMyQta",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2wOmw7inuyOSURsfyQcwLjMyQta/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2wOmw7inuyOSURsfyQcwLjMyQta"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
