# Integration: {{Service_Name}}

## 🔗 API Connectivity
* **Provider:** {{Provider_Name}}
* **Base URL:** `https://api.{{provider}}.com/v1`
* **Endpoint:** `{{/path}}`
* **Method:** `{{METHOD}}`
* **Auth Type:** `{{AUTH_TYPE}}`

---

## 🔑 Authentication Headers
| Header Key | Expected Value | Required |
| :--- | :--- | :--- |
| **Content-Type** | `application/json` | Yes |
| **Authorization** | `Bearer {{API_KEY}}` | Yes |

---

## 📦 Request Payload (Standard JSON)
```json
{
  "model": "{{model_id}}",
  "messages": [
    {
      "role": "system",
      "content": "{{system_prompt}}"
    },
    {
      "role": "user",
      "content": "{{user_input}}"
    }
  ],
  "temperature": {{0.7}},
  "max_tokens": {{1000}},
  "stream": {{false}}
}
```
---

## 🏗️ n8n Configuration Logic
* **Node Type:** `HTTP Request`
* **Authentication:** `Header Auth`
* **Body Parameters:** `JSON`
* **Error Handling:** `{{Logic}}`

---

## 📥 Sample Response Schema
```json
{
  "id": "{{id}}",
  "choices": [
    {
      "message": {
        "content": "{{response}}"
      }
    }
  ],
  "usage": {
    "total_tokens": 0
  }
}
```

---

---

## 🛠️ Developer Resources
* **Official SDK:** [Link]
* **API Reference:** [Link]
