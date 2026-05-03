# MiMSMS API Documentation

Fast, reliable, and developer-friendly Bulk SMS API for Bangladesh.

---

## 🚀 Base URL
https://api.mimsms.com

---

## 🔐 Authentication
Use API Key in request headers:

Authorization: Bearer YOUR_API_KEY

---

## 📩 Send SMS
### Endpoint
POST /send-sms

### Example Request (cURL)
```bash
curl -X POST https://api.mimsms.com/send-sms \
-H "Authorization: Bearer YOUR_API_KEY" \
-H "Content-Type: application/json" \
-d '{
  "to": "01XXXXXXXXX",
  "message": "Hello from MiMSMS"
}'
