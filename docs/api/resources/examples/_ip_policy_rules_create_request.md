<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"action":"allow","cidr":"212.3.14.0/24","description":"nyc office","ip_policy_id":"ipp_2vZ9VX6MoW9ZZDP04EaXJgUk8BC"}' \
https://api.ngrok.com/ip_policy_rules
