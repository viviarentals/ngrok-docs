<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-04-11T03:22:33Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2vZ9VbY1hbxvBOzeHKKySp5hXbg",
          "uri": "https://api.ngrok.com/event_destinations/ed_2vZ9VbY1hbxvBOzeHKKySp5hXbg"
        }
      ],
      "id": "esb_2vZ9Vcy2oU0CKVY0mhV9aCxA36w",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2vZ9Vcy2oU0CKVY0mhV9aCxA36w/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2vZ9Vcy2oU0CKVY0mhV9aCxA36w"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
