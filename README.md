
---

### ✅ How to Practice Markdown
1. Use a free online editor:
   - [Dillinger.io](https://dillinger.io/)
   - [StackEdit](https://stackedit.io/)
2. Or open a `.md` file in [VS Code](https://code.visualstudio.com/)

Try writing:
- A small README
- A sample API endpoint doc
- A step-by-step user guide

---

### 🔧 Task for You (Do This Now)
Create a file called `send-document-api.md` and paste this content:

```md
# Send Document API

## Overview
This API allows you to send a document to a recipient for digital signing.

---

## Endpoint

**POST** `/sendDocument`

## Headers
- `Authorization: Bearer <your-api-key>`

## Request Body
```json
{
  "recipient": "user@example.com",
  "documentId": "doc-123"
}
