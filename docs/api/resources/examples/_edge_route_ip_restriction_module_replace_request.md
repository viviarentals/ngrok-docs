<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vZ9VuU7M11frVkpB8diVpnBQnG","ipp_2vZ9VvUDJERzA9pZT0BodD7QYCq"]}' \
https://api.ngrok.com/edges/https/edghts_2vZ9VrbWbVDzARzvLhh8CdC8Sh8/routes/edghtsrt_2vZ9VtNCIX5wIkcz6PzuLvY215X/ip_restriction
