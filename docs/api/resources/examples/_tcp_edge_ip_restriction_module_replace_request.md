<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vZ9WIoTzHczaKbjmBO5WRsfZ3L"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2vZ9WCHUaYUKM0m47OrqW3o3atk/ip_restriction
