<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vZITWM60xAe7eaII4CLtfHfS2F","ipp_2vZITbffFB9m6qwI2VhxeDL5OlJ"]}' \
https://api.ngrok.com/edges/https/edghts_2vZITYuW1NCOlgxN1g9GIAee6AG/routes/edghtsrt_2vZITYAk669NsobVF2Ds6tTRRPk/ip_restriction
