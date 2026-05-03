# MiMSMS API Documentation

🚀 Official Bulk SMS API for developers

---

## 🔗 Live API Portal

👉 https://api.mimsms.com (Base API Endpoint)
👉 https://apidoc.mimsms.com (Postman API Docs)
👉 https://rapidapi.com/tmsmasum/api/mimsms-bulk-sms-api (Rapid API Docs)
👉 https://app.swaggerhub.com/apis-docs/mimsms/mimsms-api/1.0.0 (Swagger Docs)

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
