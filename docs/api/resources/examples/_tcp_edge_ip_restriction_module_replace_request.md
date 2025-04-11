<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vZITyZwxrZj41NUnXooaV6P1fl"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2vZITtxfhcOBkITwQWHJAsPx5oO/ip_restriction
