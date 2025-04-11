<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"x-frontend":"ngrok"},"enabled":true,"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2vZ9W2NpRvUSrO3PVNLPK9z8aNY/routes/edghtsrt_2vZ9Vz87olAhCB7wLiSPKLHX2LI/request_headers
