````md id="hzk8hm"

## Architecture


Frontend UI (HTML/CSS/JS)
        ↓
Webhook API (n8n)
        ↓
OpenAI Processing
        ↓
JSON Parsing
        ↓
Dynamic Result Rendering


# AI Email Classification API

AI-powered email analysis system with frontend UI, automatic classification, risk assessment and response generation.

## Features

- AI email classification
- Automatic reply decision system
- Risk analysis
- Spam detection
- Confidence scoring
- Professional AI-generated responses
- User Mode / Dev Mode
- Frontend UI
- JSON API architecture
- Webhook integration with n8n
- OpenAI integration

---

## Categories

The system can classify emails into:

- offer
- complaint
- invoice
- spam
- partnership
- recruitment
- support
- legal
- private
- other

---

## AI Decision Logic

The AI evaluates:

- whether the email is safe to answer automatically,
- whether human intervention is required,
- spam probability,
- response confidence,
- business intent,
- risk level.

---

## Tech Stack

Frontend:
- HTML
- CSS
- JavaScript

Backend / Automation:
- n8n
- Webhooks

AI:
- OpenAI API

Deployment:
- Vercel
- GitHub

---

## User Mode

Clean business-oriented UI for normal usage.

Displays:
- category
- confidence
- decision
- generated response
- reasoning

---

## Dev Mode

Developer/debug mode with raw JSON output.

Useful for:
- testing
- API debugging
- prompt engineering
- integration checks

---

## Example Response

```json
{
  "category": "offer",
  "spam": false,
  "can_reply": true,
  "confidence": 0.94,
  "reason": "Business inquiry regarding process automation.",
  "reply": "Professional AI-generated response..."
}
````

---

## Live Demo

https://response-api-six.vercel.app/

---

## Screenshots

(Add screenshots here)

---

## Future Improvements

* Authentication
* API keys
* PDF invoice analysis
* Multi-agent AI architecture
* CRM integration
* Conversation memory
* Dashboard analytics
* History panel
* User accounts
* Vector database integration

---

## Author

Mantini94

```
```
