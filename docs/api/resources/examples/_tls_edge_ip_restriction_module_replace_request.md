<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vZITzfMQzT4mOd47qGBgbDqQBA","ipp_2vZITx8SanWImmQY3dBbjKJIfdi"]}' \
https://api.ngrok.com/edges/tls/edgtls_2vZIU0oouAbmnxueamgODuhX4zd/ip_restriction
