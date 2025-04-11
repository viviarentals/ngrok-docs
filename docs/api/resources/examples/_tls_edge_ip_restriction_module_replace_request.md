<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vZ9WFQ2BHWhwjnNxfyuxuqP8ON","ipp_2vZ9WIfwZnKf4h3kdXoLqzumaxT"]}' \
https://api.ngrok.com/edges/tls/edgtls_2vZ9WGyNRis0NqHfXIGWJNUQD5a/ip_restriction
