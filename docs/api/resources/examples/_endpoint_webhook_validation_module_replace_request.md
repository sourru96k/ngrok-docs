
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"provider":"TWILIO","secret":"secret_token"}' \
https://api.ngrok.com/endpoint_configurations/ec_2GjEzJ2fskcBbTAjCRt6hDxAONG/webhook_validation
